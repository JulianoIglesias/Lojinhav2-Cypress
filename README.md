# Apresentação

* Trata-se de uma breve apresentação dos comandos básicos do framework Cypress, baseados no curso Básico para Cypress.

# Aplicação

A aplicação se chama Lojinhav2, criada pelo professor Júlio de Lima

## Funcionalidades da aplicação

A aplicação Lojinhav2 é basicamente uma loja virtual, onde você pode precificar e adicionar acessórios aos seus produtos.

# Pré-requisitos

Antes de começar, garanta que os seguintes sistemas estejam instalados em seu computador.

- [git](https://git-scm.com/) 
- [Node.js](https://nodejs.org/en/) 
- npm
- [Google Chrome](https://www.google.com/intl/pt_br/chrome/) 
- [Visual Studio Code](https://code.visualstudio.com/)


> **Obs. 2:** Ao instalar o Node.js o npm é instalado junto.

> **Obs. 3:** Para verificar as versões do git, Node.js e npm instaladas em seu computador, execute o comando `git --version && node --version && npm --version` no seu terminal de linha de comando.

## Instalação e inicialização do [Cypress](https://cypress.io) 🌲

1. Na raiz do projeto, execute o comando `npm install cypress@9.5.1 --save-dev` (ou `npm i cypress@9.5.1 -D` para a versão curta)
2. Logo após, execute o comando `npx cypress open` para abrir o Cypress pela primeira vez
3. Por fim, com o _Test Runner_ aberto, delete os exemplos criados automaticamente, crie um arquivo chamado `CAC-TAT.spec.js` e feche o _Test Runner_.

> **Obs. 2:** Quando inicializado pela primeira vez, o Cypress automaticamente cria o arquivo `cypress.json` e o diretório `cypress/`, com os sub-diretórios `fixtures/`, `integration/`, `plugins/` e `support/`, com seus respetivos arquivos (com exceção dos exemplos, que acabamos de deletar).

# Documentação Oficial
* https://docs.cypress.io/guides/overview/why-cypress
