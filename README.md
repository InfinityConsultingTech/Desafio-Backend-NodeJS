# API de Gerenciamento de Biblioteca

Este é um projeto de API para gerenciar uma biblioteca, permitindo que usuários aluguem e devolvam livros, incluindo autenticação para garantir a segurança das operações.

## Funcionalidades

### Autenticação

- Registro de usuários.
- Login de usuários.
- Operações relacionadas à biblioteca exigem autenticação.

### CRUD de Livros

- Adição de um novo livro à biblioteca.
- Listagem de todos os livros disponíveis.
- Detalhes de um livro específico.

### Aluguel e Devolução de Livros

- Aluguel de um livro (após autenticação).
- Listagem de livros alugados por um usuário (após autenticação).
- Devolução de um livro (após autenticação).

## Modelo de Dados

- Usuários (id, nome, email, senha hash).
- Livros (id, título, autor, disponibilidade).
- Histórico de aluguéis (id do usuário, id do livro, data de aluguel, data de devolução).

## Tecnologias Utilizadas

- [NestJS](https://nestjs.com/) como framework.
- [Prima ORM](https://www.prisma.io/) para operações no banco de dados.

## Requisitos Técnicos

- [Node.js](https://nodejs.org/) e [npm](https://www.npmjs.com/) instalados.

## Bonus

- Testes Unitarios
- Configuração do ambiente para [Docker](https://www.docker.com/) para facilitar o gerenciamento do banco de dados.

## Entrega

Para fazer a entregar, basta subir projeto no seu github, deixar o repositório público e enviar o link do repo no email `contato@infitinyconsulting.io`

---

Certifique-se de fornecer instruções adicionais ou detalhes específicos do ambiente, se necessário. Este README básico serve como um ponto de partida para os usuários do projeto.
