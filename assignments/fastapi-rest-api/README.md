# 📘 Assignment: Construindo APIs REST com FastAPI

## 🎯 Objective

Aprender a criar APIs REST usando o framework FastAPI em Python. Você construirá uma API simples para gerenciar uma lista de tarefas (to-do list).

## 📝 Tasks

### 🛠️	Criar Endpoints Básicos

#### Description
Implemente endpoints para criar, ler, atualizar e deletar (CRUD) itens da lista de tarefas.

#### Requirements
Completed program should:

- Ter um endpoint GET /todos para listar todas as tarefas
- Ter um endpoint POST /todos para criar uma nova tarefa
- Ter um endpoint PUT /todos/{id} para atualizar uma tarefa existente
- Ter um endpoint DELETE /todos/{id} para deletar uma tarefa
- Usar modelos Pydantic para validação de dados


### 🛠️	Adicionar Funcionalidades Avançadas

#### Description
Adicione funcionalidades como filtros, paginação e tratamento de erros.

#### Requirements
Completed program should:

- Suportar query parameters para filtrar tarefas por status (pendente/concluída)
- Implementar paginação nos resultados
- Retornar respostas de erro apropriadas (404 para não encontrado, 400 para dados inválidos)
- Incluir documentação automática com Swagger UI