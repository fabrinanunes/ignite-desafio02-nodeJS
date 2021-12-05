# Ignite - Trilha NodeJS

## 💻 Desafio 02 - Trabalhando com Middlewares

O desafio consiste na criação de uma aplicação para gerenciar tarefas (em inglês *todos*). 
É permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*. Neste desafio, há um plano grátis onde o usuário só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

### Sobre os TO-DOS
- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico (o `username` será passado pelo header).