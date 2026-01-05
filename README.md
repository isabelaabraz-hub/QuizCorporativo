# Quiz Interativo CapriShow

Projeto de Front-End desenvolvido para aplicar conhecimentos de lógica de programação e desenvolvimento web. A aplicação consiste em um jogo de perguntas e respostas sobre a marca Capricche, com temporizador e feedback visual.

## Sobre o Projeto

O objetivo principal deste projeto foi praticar a manipulação do DOM (Document Object Model) e o uso de estruturas de dados em JavaScript, como Arrays e Objetos, para criar uma aplicação dinâmica sem a necessidade de recarregar a página.

A interface foi construída pensando na usabilidade, alterando a imagem de fundo dinamicamente conforme a pergunta apresentada ao usuário.

## Tecnologias e Conceitos Aplicados

* **HTML5:** Estruturação semântica da página.
* **CSS3:** Estilização com Flexbox para layout, uso de variáveis globais e importação de fontes personalizadas (@font-face).
* **JavaScript:**
    * Manipulação de eventos (Event Listeners).
    * Estruturas de controle e repetição (if/else, forEach).
    * Funções assíncronas básicas (setInterval, clearInterval) para o temporizador.
    * Manipulação de Arrays de Objetos para armazenar as perguntas e respostas.

## Funcionalidades Implementadas

1.  **Carregamento Dinâmico:** As perguntas não estão explícitas no HTML, mas são renderizadas via JavaScript a partir de um Array de objetos.
2.  **Lógica de Pontuação:** O sistema valida a resposta clicada (dataset) comparando com o gabarito no objeto e soma pontos se correta.
3.  **Temporizador:** Implementação de um contador regressivo de 30 segundos por pergunta.
4.  **Feedback de Erro/Acerto:** Mudança visual imediata nos botões (classes CSS .correta e .incorreta) ao selecionar uma opção.
5.  **Relatório Final:** Ao encerrar o quiz, a aplicação percorre o array de erros acumulados e gera um relatório HTML injetado na página.

## Como Executar

Para rodar o projeto localmente, não é necessária instalação de dependências ou servidores complexos, pois é um projeto estático.

1.  Baixe os arquivos deste repositório.
2.  Mantenha a estrutura de pastas (css, js, imagens, fonts).
3.  Abra o arquivo "index.html" no navegador.

## Estrutura do Código

* **index.html:** Ponto de entrada, contém as divs container que serão populadas pelo JS.
* **arquivos.css:** Contém as regras de estilo, incluindo animações de transição de background.
* **arquivos.js:** Contém toda a lógica de negócio (funções iniciarQuiz, mostrarPergunta, selecionarResposta).

## Autor

[01861647 Isabela Maria de Alencar Braz]
[01824297 Eduardo Gonçalves da Luz Silva]
[01800086 Leandro Gonçalves Correia Junior]
Estudante de Análise e Desenvolvimento de Sistemas 
Turma 2NA 