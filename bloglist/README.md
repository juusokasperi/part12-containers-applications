# Bloglist -app

```
Before building, remember to add .env file to ./backend/, containing:
MONGODB_URI=link_to_mongodb
TEST_MONGODB_URI=link_to_testing_mongodb
SECRET=secret_random_string_for_jwt
```

## Build & run in development mode

```
docker compose -f docker-compose.dev.yml up
```

Server running in dev mode at http://localhost:8000

## Build & run in production mode

```
docker compose -f docker-compose.yml up
```

Server running in production mode at http://localhost:8000

## Api access

```
http://localhost:8000/api/blogs/
http://localhost:8000/api/users/
```
