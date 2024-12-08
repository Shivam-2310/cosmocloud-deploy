CosmoCloud DevOps Project
📌 Project Overview
This Kubernetes deployment configuration sets up a scalable, multi-service web application with a frontend, backend, and Redis database. The project demonstrates a microservices architecture using Kubernetes deployments and services.
🏗️ Architecture
Components

Frontend: Web interface
Backend: Application logic
Redis: In-memory data store

System Design
Copy[Frontend Service] <-> [Backend Service] <-> [Redis Service]
🛠️ Prerequisites
Before you begin, ensure you have:

Kubernetes cluster (Minikube, Kind, or cloud-based)
kubectl command-line tool
Docker (optional)