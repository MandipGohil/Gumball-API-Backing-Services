# Gumball-API-Backing-Services

# 1. Docker Images Needed will include:
docker pull golang:latest
docker pull mongo:latest
docker pull rabbitmq:3-management
docker pull kong:0.9.9
docker pull cassandra:2.2

# 2. You are to make minor modifications to the code and then deploy into Docker

# 3. Docker Containers:
Go Code will be an API deployed to a Docker Container using golang:latest as Base Image
MongoDB will be deployed to a Docker Container
RabbitMQ will be deployed to a Docker Container
Kong and Cassandra will be deployed to Docker Containers

# 4. Container Configurations:
Node.js App will be Frontend (running on localhost) connected to Kong API Gateway Docker Container
Go API Server will connect to RabbitMQ and MongoDB
Kong API Gateway will connect to Cassandra Container (as in Starbucks Lab v3)
Kong API Gateway will be configured to forward API calls to Go API Container as Upstream Server

# Download the Source for the Project Folder.
goapi
nodejs
