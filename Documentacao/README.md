# Solução Venx_Solar

# Projeto backend Com AdonisJs

Este é um projeto backend que utiliza AdonisJs. Este guia irá te ajudar a clonar o repositório e executar localmente o projeto.

## Pré-requisitos

Certifique-se de ter os seguintes softwares instalados em sua máquina:

- [Node.js](https://nodejs.org/) (Versão 14 ou superior)
- [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)
- [PostgresSQL]

## Clonando o Repositório

bash
git clone https://github.com/gabrielmds222/Venx_Solar.git
cd Venx_Solar


# API Pagamentos

Esta é uma api para gestão de descontos em faturas e uso da API de cobrança do banco do Brasil(https://www.bb.com.br/site/developers/apis-para-o-seu-negocio/api-cobranca/) para a emissão de boletos com o desconto implementado


### Iniciando projeto

```
  npm run dev
```

# API Login

Esta é uma api com de login com token de autenticação e um CRUD de usuários e criação de grupos


## Documentação da API

#### Instalação node_modules

```
  npm install
```
#### Ou

```
  yarn add
```

#### Iniciando projeto

```
  npm run start
```

##Configuração do Bando de dados

```
DB_CONNECTION=pg
DB_HOST=127.0.0.1
DB_PORT=5432
DB_USER=usuario
DB_PASSWORD=senha
DB_DATABASE=nome_do_banco
```

## Migrations
```
node ace migration:run
```

##Rodando servidor
```
npm run dev
```
