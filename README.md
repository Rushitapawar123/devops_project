# Docker Web Server

A static website served by Nginx inside a Docker container.

## Features
- Custom Dockerfile (nginx:alpine)
- Health check endpoint (/health)
- Docker Compose setup with volumes and restart policy

## How to run
docker compose up -d --build

Open http://localhost:8080