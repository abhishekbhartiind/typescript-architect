## TypeScript

```bash
src
|- Bootstrap.ts
|- Database.ts
```

Here, In src directory, you will find `Bootstrap.ts` and `Database.ts`.
In Database, you will find interface and todo create method
In Bootstrap, we have Repository, Services and Controller classes

`TodoRepository`: Contains logic of Database & save method func
`TodoService`: Calls TodoRepository which implements `createTodo` function which calls save method of TodoRepository. Logic validation are implemented here
`TodosController`: Calls TodoService and its method

Run This Repo

```bash
yarn run:dev
```
