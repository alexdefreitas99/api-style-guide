# API Style Guide

- [Resource](#resource)

## Resource

É uma abstração de uma informação (normalmente entidades de negócio) gerenciada por uma aplicação. o Recurso representa uma coleção onde cada elemento possui um identificador único.
Portanto, o recurso deve ser representado no plural.

POST /cartoes
GET /cartoes
GET /cartoes/{id}
