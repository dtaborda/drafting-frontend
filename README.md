# Getting Started with Create React App

## Available Scripts

### `docker build -f Dockerfile.dev .`

### `docker run -p 3000:3000 ${docker img ID} .`

### `docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app ${docker img ID} .`

## Production nginx

### `docker build .`

### `docker run -p 8080:80 ${docker img ID} .`
