# Estilo Arquitetural Rest com NodeJS

Entendendo o projeto de arquitetura Rest API com node.js

Composição do nosso projeto
Neste projeto Temos alguns Endpoints Base que podem ser extendidos da forma mais adequada para seu contexto.

# São eles:

## Usuários
* GET /users
* GET /users/:uuid
* POST /users
* PUT /users/:uuid
* DELETE /users/:uuid

## Autenticação
* POST /token
* POST /token/validate
