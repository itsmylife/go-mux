# go-mux
## Simple REST API with unit tests

Source: https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql


docker instance for postgres:
```bash
docker run -it -p 5432:5432 -d postgres
```

export variables before run the application/tests

env variable:

```bash
export APP_DB_USERNAME=postgres
export APP_DB_PASSWORD=
export APP_DB_NAME=postgres
```
