# crud
CRUD completo template.
### Requisições
#### Post

```http
  POST http://localhost:8080/basiccrud/
```


#### Get by id

```http
  GET http://localhost:8080/basiccrud/${id}
```

| Parâmetro | Tipo     | Descrição                |
| :-------- | :------- | :------------------------- |
| `id` | `Long` | **OBRIGATORIO**. id que deseja obter |

#### Get by name

```http
  GET http://localhost:8080/basiccrud/${name}
```

| Parâmetro | Tipo     | Descrição                |
| :-------- | :------- | :-------------------------------- |
| `name`      | `string` | **OBRIGATORIO**. nome que deseja obter  |

#### Delete

```http
  DELETE http://localhost:8080/basiccrud/${id}
```

| Parâmetro | Tipo     | Descrição                |
| :-------- | :------- | :-------------------------------- |
| `id`      | `Long` | **OBRIGATORIO**. id que deseja deletar  |
