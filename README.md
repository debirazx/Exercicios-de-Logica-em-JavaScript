# 💻 Exercícios de Lógica de Programação (JavaScript)

Repositório destinado ao armazenamento de atividades práticas desenvolvidas na **UNIFOR (Universidade de Fortaleza)** para o curso de **Ciência da Computação**.

---

## 🧠 Exercício 1: Verificação de Aposentadoria (Simplificada)

O objetivo deste exercício é criar um programa que solicite dados do usuário e valide o direito à aposentadoria com base em regras específicas de idade e tempo de serviço.

### 📝 Tarefa
Solicitar do usuário:
* **Idade**
* **Tempo de contribuição**

### 📋 Requisitos para Aposentadoria
De acordo com os critérios estabelecidos no enunciado:
1. Ter **65 anos** ou mais;
2. **OU** ter contribuído por **30 anos** ou mais **E** ter pelo menos **60 anos** de idade.

### 🛠️ Tecnologias e Conceitos Aplicados
* **Interação com Usuário:** Uso de `prompt()` e `document.write()`.
* **Tratamento de Dados:** Conversão de valores com `parseInt()` e `parseFloat()`.
* **Lógica de Programação:** Estrutura condicional `if / else` e operadores lógicos (`&&` e `||`).

## 🚀 Como visualizar o projeto

Como este projeto foi desenvolvido em HTML e JavaScript puro, você não precisa instalar nada pesado:

1. Faça o download do arquivo `Aposentadoria.html` deste repositório.
2. Localize o arquivo na sua pasta de Downloads.
3. Clique com o botão direito no arquivo e escolha **"Abrir com"** -> **Google Chrome** (ou seu navegador de preferência).
4. O navegador abrirá janelas pedindo sua idade e tempo de contribuição, e mostrará o resultado na tela!

---

## 🧠 Exercício 2: Validação de Aprovação de Aluno

Este sistema avalia a situação acadêmica de um aluno, calculando médias parciais e finais, além de validar o percentual de frequência obrigatório.

## 📝 Tarefa
Solicitar do usuário:
* Nome do aluno
* Notas das provas (AV1, AV2 e AV3)
* Percentual de frequência

## 📋 Requisitos para Aprovação (Regras de Negócio)

* **Nota Parcial**: Média entre AV1 e AV2.
* **Bloqueio de AV3**: O aluno só pode realizar a AV3 se a Nota Parcial for igual ou superior a 4. Caso contrário, é "Reprovado na Parcial".
* **Nota Final**: Média entre a Nota Parcial e a AV3.
* **Critérios de Sucesso**: O aluno é aprovado se tiver Nota Final >= 5 **E** Frequência >= 75%.

## 🛠️ Tecnologias e Conceitos Aplicados

* **Entrada e Saída**: Uso de `prompt()` para captura e `console.log()` para exibição de resultados.
* **Tipagem**: Uso de `parseFloat()` para garantir cálculos precisos com casas decimais.
* **Lógica Avançada**: Estruturas de `if / else` aninhadas para controle do fluxo da disciplina.

## 🚀 Como visualizar o projeto

* Faça o download do arquivo `Media.html`.
* Abra no seu navegador de preferência.
* Pressione `F12` e clique na aba **Console** para ver as mensagens de aprovação ou reprovação.

---
*Projeto desenvolvido para a disciplina de Raciocínio Lógico Algorítmico (RLA) - UNIFOR.*
