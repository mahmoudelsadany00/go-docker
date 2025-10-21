# Go Docker App
Simple Go web server containerized with Docker.

## Run locally (without Docker)
go run main.go

## Run with Docker
docker build -t <DOCKERHUB_USER>/go-docker-app:latest .
docker run -p 8080:8080 <DOCKERHUB_USER>/go-docker-app:latest

## Docker Hub
Docker image: https://hub.docker.com/r/<DOCKERHUB_USER>/go-docker-app
