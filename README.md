# CRUD de Registro de Usuário

Este é um projeto de CRUD (Create, Read, Update, Delete) para registro de usuários, desenvolvido utilizando **React.js** no frontend, **Node.js** com **Express.js** no backend e **MongoDB** como banco de dados.

## Tecnologias Utilizadas

- **Frontend**: React.js, Axios, React Hooks
- **Backend**: Node.js, Express.js, Mongoose
- **Banco de Dados**: MongoDB 

## Funcionalidades

- Criar novos usuários com nome, idade e email
- Listar todos os usuários cadastrados
- Excluir usuários do banco de dados
- Integração entre frontend e backend via API REST

## Como Executar o Projeto

### 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd user-registration
```

### 2. Configurar o Backend
```bash
cd backend
npm install
```

#### 2.1 Configurar variáveis de ambiente
Crie um arquivo **.env** na raiz da pasta `api-nodejs` com as seguintes configurações:
```env
PORT=3000
MONGO_URI=mongodb+srv://<USUARIO>:<SENHA>@<CLUSTER>.mongodb.net/<BANCO>
JWT_SECRET=sua_chave_secreta
```
> **Importante**: Não compartilhe seu arquivo `.env`. Adicione-o ao `.gitignore`.

#### 2.2 Iniciar o servidor
```bash
node --watch server.js
```
O backend estará rodando em `http://localhost:3000`

### 3. Configurar o Frontend
```bash
cd front-react
npm install
```

#### 3.1 Iniciar o React
```bash
npm run dev
```
O frontend estará disponível em `http://localhost:5173`

## Banco de Dados
O projeto utiliza **MongoDB** como banco de dados principal. Certifique-se de configurar corretamente a variável `MONGO_URI` no arquivo `.env` para conectar ao seu banco.

## Rotas da API

### Usuários

- **POST /api/users** - Criar novo usuário
- **GET /api/users** - Listar todos os usuários
- **DELETE /api/users/:id** - Excluir usuário




----------------------------------------------------------


# User Registration CRUD

This is a CRUD (Create, Read, Update, Delete) project for user registration, developed using **React.js** on the frontend, **Node.js** with **Express.js** on the backend and **MongoDB** as the database.

## Technologies Used

- **Frontend**: React.js, Axios, React Hooks
- **Backend**: Node.js, Express.js, Mongoose
- **Database**: MongoDB

## Features

- Create new users with name, age and email
- List all registered users
- Delete users from the database
- Integration between frontend and backend via REST API

## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-user/repository-name.git
cd user-registration
```

### 2. Configure the Backend
```bash
cd backend
npm install
```

#### 2.1 Configure environment variables
Create a **.env** file in the root of the folder `api-nodejs` with the following settings:
```env
PORT=3000
MONGO_URI=mongodb+srv://<USER>:<PASSWORD>@<CLUSTER>.mongodb.net/<BANK>
JWT_SECRET=your_secret_key
```
> **Important**: Do not share your `.env` file. Add it to `.gitignore`.

#### 2.2 Start the Server
```bash
node --watch server.js
```
The backend will be running at `http://localhost:3000`

### 3. Configure the Frontend
```bash
cd front-react
npm install
```

#### 3.1 Start React
```bash
npm run dev
```
The frontend will be available at `http://localhost:5173`

## Database
The project uses **MongoDB** as the main database. Make sure to correctly configure the `MONGO_URI` variable in the `.env` file to connect to your database.

## API Routes

### Users

- **POST /api/users** - Create new user
- **GET /api/users** - List all users
- **DELETE /api/users/:id** - Delete user

