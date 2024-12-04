# Projeto Node.js - Autenticação JWT e CRUD de Produtos

## Descrição

Este projeto consiste em uma API construída com Node.js, que oferece autenticação via JWT (JSON Web Token) e um CRUD (Criar, Ler, Atualizar, Excluir) simples de produtos. A API também inclui uma funcionalidade para upload de arquivos, onde o usuário pode associar uma imagem ao produto e obter a URL da imagem armazenada.

### Funcionalidades
- **Autenticação de usuários**: Login, Cadastro, Atualização e Exclusão de cadastro via JWT.
- **CRUD de Produtos**: Adicionar, Editar, Listar e Excluir produtos. Apenas usuários autenticados podem realizar essas ações.
- **Upload de Arquivos**: Rota para envio de imagens, com retorno da URL da imagem associada ao produto.

## Tecnologias Utilizadas
- **Node.js**: Para construção da API.
- **Express**: Framework para criação de APIs.
- **JWT (JSON Web Token)**: Para autenticação de usuários.
- **Sequelize**: ORM para manipulação do banco de dados.
- **PostgreSQL (ou outro banco de sua escolha)**: Banco de dados utilizado para armazenar as informações de usuários e produtos.
- **Multer**: Middleware para upload de arquivos.

## Pré-requisitos

Antes de rodar o projeto, verifique se você possui as seguintes ferramentas instaladas:
- **Node.js** (versão recomendada: 14 ou superior).
- **npm** (gerenciador de pacotes do Node.js).
- **PostgreSQL** ou outro banco de dados de sua escolha.

## Como rodar o projeto
npm start


