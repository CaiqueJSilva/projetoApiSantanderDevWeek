API de Gerenciamento de Livros
Este projeto é uma API simples desenvolvida em Flask para gerenciamento de livros, com operações CRUD (Create, Read, Update, Delete).

Funcionalidades
Consultar todos os livros: GET /livros

Consultar livro por ID: GET /livros/<id>

Adicionar novo livro: POST /livros

Editar livro existente: PUT /livros/<id>

Excluir livro: DELETE /livros/<id>

Estrutura dos Dados
Cada livro possui:

id (identificador único)

titulo (título do livro)

autor (autor do livro)

Tecnologias Utilizadas
Python

Flask (microframework web)

JSON para transferência de dados

A API roda localmente na porta 5000 (localhost:5000) com modo debug ativado para desenvolvimento.
