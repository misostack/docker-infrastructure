# Docker Infrastructure

## Includes

- Docker compose for common database types
- Docker compose for common tools
- Docker compose for common stack: nodejs, php, python, ...
- Docker cheatsheet

## Todo

1. [ ] Redis
2. [ ] MySQL
3. [ ] Postgresql

## Docker Cheatsheet

### Docker restart policies

There are following restart policies for Docker containers:

- no: The default behavior is to not start containers automatically
- always: Always restart a stopped container unless the container was stopped explicitly
- unless-stopped: Restart the container unless the container was in stopped state before the Docker daemon was stopped (explained later)
- on-failure: Restart the container if it exited with a non-zero exit code or if the docker daemon restarts

## Version

- https://docs.docker.com/compose/compose-file/compose-versioning/
