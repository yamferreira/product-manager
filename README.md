# CRUD de Produtos

Aplicação full stack para gerenciamento de produtos, desenvolvida com **Java Spring Boot** no back-end e **React** no front-end.

O sistema permite:

* Cadastrar produtos
* Listar produtos
* Atualizar produtos
* Remover produtos

A interface foi desenvolvida em React e se comunica com uma API REST construída com Spring Boot.

## Tecnologias Utilizadas

### Back-end

* Java
* Spring Boot
* Spring Data JPA
* MySQL
* Maven

### Front-end

* React
* JavaScript
* Axios

## Estrutura do Projeto

```text
monorepo/
├── backend/
└── frontend/
```

## Como Executar o Projeto

### Pré-requisitos

* Java 17 ou superior
* Node.js
* npm
* MySQL
* Maven

---

## Executando o Back-end

Entre na pasta do back-end:

```bash
cd backend
```

Configure as credenciais do banco de dados no arquivo:

```text
src/main/resources/application.properties
```

Execute a aplicação:

```bash
mvn spring-boot:run
```

A API ficará disponível em:

```text
http://localhost:8080
```

---

## Executando o Front-end

Em outro terminal, entre na pasta do front-end:

```bash
cd frontend
```

Instale as dependências:

```bash
npm install
```

Inicie a aplicação:

```bash
npm run dev
```

ou

```bash
npm start
```

(dependendo da configuração do projeto)

O front-end ficará disponível em:

```text
http://localhost:3000
```

ou

```text
http://localhost:5173
```

(dependendo da ferramenta utilizada)

## Funcionalidades

* Cadastro de produtos
* Edição de produtos
* Exclusão de produtos
* Listagem de produtos
* Integração entre React e Spring Boot via API REST

## Objetivo

Este projeto foi desenvolvido com fins de estudo para praticar o desenvolvimento de aplicações full stack utilizando React no front-end e Spring Boot no back-end, aplicando conceitos de APIs REST, persistência de dados e integração entre sistemas.
