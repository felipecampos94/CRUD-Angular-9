# CRUD-Angular-9

O CRUD-Angular-9 é uma aplicação web desenvolvida utilizando o framework Angular 9 que tem como objetivo demonstrar um CRUD (Create, Read, Update, Delete) simples.

## Funcionalidades

O CRUD-Angular-9 possui as seguintes funcionalidades:

- Listagem de itens cadastrados
- Cadastro de novos itens
- Edição de itens existentes
- Exclusão de itens existentes

## Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina o [Node.js](https://nodejs.org/en/) e o [Angular CLI](https://cli.angular.io/). 

## Instalação

Para instalar e executar a aplicação, siga os seguintes passos:

1. Clone o repositório em sua máquina utilizando o comando `git clone https://github.com/seu-usuario/crud-angular-9.git`.
2. Acesse o diretório raiz do projeto através do terminal.
3. Execute o comando `npm install` para instalar as dependências do projeto.

## Executando a aplicação

### Frontend

Para executar a aplicação frontend localmente, siga os seguintes passos:

1. Abra o terminal na pasta raiz do projeto.
2. Execute o comando `ng serve` para compilar e servir a aplicação.
3. Abra o navegador e acesse o endereço `http://localhost:4200`.

A aplicação será carregada no navegador e estará pronta para uso.

### Backend

Para executar a aplicação backend localmente, siga os seguintes passos:

1. Abra o terminal na pasta `backend` do projeto.
2. Execute o comando `npm start` para iniciar o servidor.
3. O servidor estará rodando na porta `3000`.

## Gerando build de produção

Para gerar uma versão de produção da aplicação frontend, execute o seguinte comando:

```bash
ng build --prod
