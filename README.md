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

#### `Configure seu Banco de dados no "config.env" e no "seeder"`
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
