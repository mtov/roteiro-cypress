# Roteiro de Testes E2E Usando Cypress

## Aplicação Alvo

Neste roteiro vamos testar uma aplicação simples de criação de lista de tarefas, chamada TodoMVC, cujo repositório se encontra [aqui](https://github.com/tastejs/todomvc).

Para facilitar, copiamos o código dessa aplicação, especificamente a implementação baseada em JavaScript ES5, para este diretório. Ou seja, com isso, você vai fazer o roteiro integralmente neste repositório. Basta, primeiro, cloná-lo para sua máquina local.

Depois disso, digite em um terminal aberto no diretório clonado:

```
npm run build
npm install
npm run dev
```

Em um browser, digite:

```
http://localhost:7001
```

Então, use a aplicação e experimente as suas features.

## Rodando o Primeiro Teste E2E

Em um novo terminal, abra a interface gráfica do Cypress, digitando na raiz do seu diretório:

```
npx cypress open
```

Então escolha: "E2E Testing", "Chrome" e "Start E2E Testing in Chrome".

Depois, abra um teste que já implementamos, clicando no arquivo chamado `spec.cy.js`. O teste será aberto pelo Cypress e será automaticamente executado. Isso ocorre em uma nova janela do Chrome que também foi aberta automaticamente pelo Cypress.

Estude esse primeiro teste, que está em [cypress\e2e\spec.cy.js](.\cypress\e2e\spec.cy.js)

## Exercício

Implemente mais três testes (isto é, comandos `it`) no arquivo `cypress\e2e\spec.cy.js`
