# Desafio 01 - Ignite Trilha Node

## Sobre o desafio

Nesse desafio você desenvolverá uma API para realizar o CRUD de suas *tasks* (tarefas).

A API deve conter as seguintes funcionalidades:

- Criação de uma task
- Listagem de todas as tasks
- Atualização de uma task pelo `id`
- Remover uma task pelo `id`
- Marcar pelo `id` uma task como completa
- Importação de tasks em massa por um arquivo CSV

### Rotas 

Rotas:

- `POST - /tasks`
Cria uma nova task no BD.
- `GET - /tasks`   
Lista todas as tasks no BD.
É possível realizar uma busca, filtrando as tasks pelo `title` e `description`.
Validação se existe no BD.
- `PUT - /tasks/:id` 
É possível atualizar uma task pelo `id`.
Se for enviado somente o `title`, significa que o `description` não pode ser atualizado e vice-versa.
Validação se existe no BD.
- `DELETE - /tasks/:id`
É possível deletar uma task pelo `id`.
Validação se existe no BD.
- `PATCH - /tasks/:id/complete`
É possível marcar a task como completa ou não.
Validação se existe no BD.
