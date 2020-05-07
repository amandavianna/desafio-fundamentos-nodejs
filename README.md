<h1 align="center">Fundamentos Node.js</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/amandavianna/desafio-fundamentos-nodejs">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/amandavianna/desafio-fundamentos-nodejs?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/amandavianna/desafio-fundamentos-nodejs">

  <a href="https://github.com/amandavianna/desafio-fundamentos-nodejs/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/amandavianna/desafio-fundamentos-nodejs.svg">
  </a>
</p>

<p>É uma aplicação para armazenar transações financeiras de entrada e saída, que permite o cadastro e a listagem dessas transações.</p>

## Rotas da aplicação:

- **`POST /transactions`**: A rota recebe title, value e type dentro do corpo da requisição, sendo type o tipo da transação, que deve ser income para entradas (depósitos) e outcome para saidas (retiradas);

- **`GET /transactions`**: Rota que lista todas as transações que você cadastrou até agora, junto com o valor de soma de entradas, retiradas e total de crédito.

## Como usar:

```bash
# Clone this repository
$ git clone https://github.com/amandavianna/desafio-fundamentos-nodejs

# Go into the repository
$ cd desafio-fundamentos-nodejs

# Install dependencies
$ yarn install

# Run the app
$ yarn dev:server
```
