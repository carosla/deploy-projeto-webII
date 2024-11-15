# 🛒 Shopyy - Loja online

Este repositório contém o código-fonte de um e-commerce com cadastro de usuários, produtos, carrinho de compras e tela de administrador.

## 💻 Tecnologias utilizadas

* React.JS
* Redux Toolkit
* Node.js
* Express
* MongoDB
* Stripe

## 📜 Pré-Requisitos

* Node.js instalado
* npm ou yarn instalado globalmente

## 📑 Entregas
### 1º Bimestre

* Setup back-end (2 pontos): setup completo localmente do backend do projeto.
* Criando o middleware (2 pontos): definição do middleware para lidar com as requisições via API.
* Teste de API com Postman (2 pontos): criação e teste das API que serão utilizadas no projeto.
* Criando o Banco de Dados (MongoDB) (2 pontos): criação e teste do Banco de Dados para o projeto.
* CRUD completo (2 pontos): criação no back-end das rotas necessárias para o uso de CRUD no banco de dados via API.

### 2º Bimestre

* Criando a homepage (2 pontos): desenvolvimento da página inicial usando React.
* Criando a React Router DOM (2 pontos): definindo o DOM necessário para a página e a estrutura da loja.
* Gerenciando o Redux State (2 pontos): utilizando o Redux para gerenciamento dos estados.
* Filtros no front (2 pontos): criando filtro de produtos na página.
* Login do usuário (2 pontos): criando login do usuário e autenticação.

## 🔧 Instalação
### Clone o repositório
```
git clone https://github.com/carosla/deploy-projeto-webII.git
```

### Acesse o diretório do projeto
```
cd shopit-v2
```

### Instale as dependências
#### `npm install`
```
npm install
```

#### `yarn` (no backend e frontend)
```
yarn
```

#### `Configuração do Banco de Dados`
```
backend/config/config.env
backend/seeder/seeder.js
```

#### `seeder`
```
cd backend
yarn run seeder
```

#### `win-node-env`
```
cd backend
npm install -g win-node-env
```

#### `chart`
```
cd frontend
yarn add chart.js@^4.4.6
```

#### `build`
```
cd backend
npm install -g win-node-env
```

#### `prod`
```
cd backend
yarn run prod
```

#### `run`
```
cd frontend
yarn run start
```


## 🔎 Orientações de utilização

1 - Acesse http://localhost:4000 no seu navegador\
2 - Crie um usuário\
3 - Utilize a barra de busca para encontrar o produto desejado\
4 - Adicione os produtos no carrinho\
OBS: Utilizando um "admin", você pode criar e alterar produtos e usuários na aba "dashboard"

## 👩🏻‍💻 Código fonte

O código-fonte React está organizado em pastas e arquivos de forma modular.

`src:`
* backend: Contém os componentes React da aplicação backend, sendo eles o configDB, controllers, middlewares, routes.
* frontend: Contém os componentes frontend da aplicação.
* App.js: Ponto de entrada da aplicação.
* package.json: Contém as dependências do projeto e scripts de execução.

## ✒️ Autores

* **Aluna e desenvolvedora** -  [Ana Carolina Neias](linkedin.com/in/anacarolinaneias/)

## 🔗 Link de acesso ao projeto
Acesse o site pelo link abaixo:\
["ShopIT - Loja Online"](https://shopit-v2-odvt.onrender.com)
