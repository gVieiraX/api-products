<h1 align="center">
    API RESTful de Produtos
</h1>

O projeto foi elaborado [nesse vídeo](https://www.youtube.com/watch?v=wlYvA2b1BWI).

## Tecnologias

- Spring Boot
- Spring Starter Web
- Spring Data JPA
- Spring Sarter Validation
- Spring Starter Hateoas
- PostgreSQL

## Como Executar

1 - Clonar repositório git

```
https://github.com/gVieiraX/api-products
```

2- Instale as dependências com Maven

## API Endpoints

A API poderá ser acessada em [localhost:8080/products](http://localhost:8080/products). O Swagger poderá ser visualizado em [localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

Para fazer as requisições HTTP abaixo, foi utilizada o Postman:

- POST /products - Registra uma novo produto.

```
      {
        "name": "Ebook",
        "value": 10,
      }
```

- GET /products - Lista os produtos
```
  {
    "idProduct": "768e0494-139d-4ae4-8b4e-d5a6049c935b",
    "name": "Ebook",
    "value": 10,
  }
```

- PUT /todos/{id} - Atualiza um prduto
```
  {
    "idProduct": "768e0494-139d-4ae4-8b4e-d5a6049c935b",
    "name": "Ebook Up",
    "value": 20,
  }
```

- DELETE /products/{id} - Remover Produto
```
Product deleted successfully.
```
