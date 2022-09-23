# Todos Express API

> ultra super simple express api for creating todos

**Do not use this in production**
Made for testing purpose and education. 


[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Todos%20Express%20API&uri=https%3A%2F%2Fgithub.com%2Ffernandobelotto%2Ftodos-express-api%2Fblob%2Fmaster%2Finsomnia.json)

## endpoints

1. Get all todos 

    ```
    GET /todos
    ```

2. Create todo

    ```
    POST /todos
    body { content: "my todo content"}
    ```

3. Update todo

    ```
    PUT /todos/{todo-id}
    body { content: "my new todo content"}
    ```
4. Delete todo

    ```
    DELETE /todos/{todo-id}
    ```