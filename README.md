# ⚓ Kubernetes Flask Monitoring Dashboard

Real-time system monitoring dashboard deployed on Kubernetes with 2 replicas.

## Tech Stack
- Python Flask
- Docker
- Kubernetes (Minikube)

## Features
- Real-time CPU, RAM, Disk monitoring
- Deployed with 2 replicas for high availability
- Kubernetes Deployment + Service

## How to Run
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
minikube service flask-service

## Concepts Demonstrated
- Kubernetes Deployments
- ReplicaSets (2 replicas)
- Kubernetes Services
- Container orchestration
