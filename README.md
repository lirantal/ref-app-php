# Dockerized PHP Application

This PHP application is running on a Docker container, and includes composer for managing dependencies.

## How to run

```sh
docker-compose --build up
```

And open up in your browser `http://localhost:8080/`.

## How to access PHP container

To access the PHP container in order to manage dependencies with composer, get the container name

```sh
docker ps
```

And then open a terminal interface into it:

```
docker exec -it <container_name> /bin/bash
cd
```