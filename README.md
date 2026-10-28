# Node.js Docker CI/CD Project

## Overview
A simple Node.js application containerized using Docker.

## Technologies Used
- Node.js
- Docker
- Git and GitHub
- GitHub Actions

## Project Files
- app.js: Node.js application
- package.json: Project configuration
- Dockerfile: Instructions to build the Docker image

## Run Locally
node app.js

Open http://localhost:3000 in your browser.

## Build Docker Image
docker build -t docker-cicd-app .

## Run Docker Container
docker run -d --name my-docker-app -p 3000:3000 docker-cicd-app

## Stop Container
docker stop my-docker-app
