# Go Docker App
Simple Go web server containerized with Docker.

## Run locally (without Docker)
```bash
go run main.go
```
## Run with Docker
```bash
docker build -t maro200/go-server:latest .
docker run --rm -p 8080:8080 maro200/go-server:latest
```


## Docker Hub
Docker image: https://hub.docker.com/r/maro200/go-server
