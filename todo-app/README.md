# Todo -app

## Build & run in development mode

```
docker compose -f ./todo-backend/docker-compose.dev.yml build
docker compose -f ./todo-frontend/docker-compose.dev.yml build
docker compose -f docker-compose.dev.yml up
```

Server running in dev mode at http://localhost:8080

## Build & run in production mode

```
docker compose -f ./todo-backend/docker-compose.yml build
docker compose -f ./todo-frontend/docker-compose.yml build
docker compose -f docker-compose.yml up
```

Server running in production mode at http://localhost:8080

## Api access

```
http://localhost:8080/api/
http://localhost:8080/api/todos/
```
