
## 💻 Sobre o Todo List

O sistema "Todo List" é uma ferramenta extremamente útil para pessoas que desejam organizar suas tarefas e compromissos de maneira eficiente. Ele permite que os usuários criem uma lista de tarefas, adicionem novas tarefas à lista, atualizem tarefas existentes e excluam tarefas concluídas.
<br>


## :rocket:Instalação
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para instalar as dependencias:

```bash
$ yarn install
```

## Rodar o app

```bash
$ yarn dev
```
## Utilizar o teste

```
yarn test
```
## Rotas

    POST /users → criar um usuário.
    GET /users/:id → pesquisa um usuário pelo id
    PATCH /users/:id/pro → atualiza o plano do usuário para PRO caso não seja
    GET /todos → lista com todas as tarefas do usuário.
    POST /todos → criar um todo.
    PUT /todos/:id → atualiza um todo.
    PATCH /todos/:id/done → atualiza a propriedade done do todo para true.
    DELETE /todos/:id → deleta um todo pela id



![todo-list](https://user-images.githubusercontent.com/88260644/209749758-aa028c63-e379-4c57-957b-18a2ce0e07fa.gif)


<h4> 🛠 Projeto foi desenvolvido utilizando as seguintes tecnologias e conceitos: <h4>

    - Node.
    - JavaScript.
    - jest.
    - uuid
    - superTest
    - Nodemon.


