# Ecommerce Backend

## Features
- Product hierarchy support
- Customer and order tracking
- Average price by category
- RESTful API with JWT/OpenID Connect
- SMS and email notifications on order
- Dockerized and ready for GCP Kubernetes deployment

## Getting Started

### Local Development
```bash
git clone https://github.com/your-org/ecommerce-backend.git
cd ecommerce-backend
docker-compose up --build
```

## Deployment to GCP with Kubernetes

### Prerequisites
- Google Cloud account and project
- GKE cluster setup
- Google Container Registry enabled

### Build and Push Docker Image
```bash
docker build -t gcr.io/YOUR_PROJECT_ID/ecommerce-backend .
docker push gcr.io/YOUR_PROJECT_ID/ecommerce-backend
```

### Apply Kubernetes Configurations
```bash
kubectl apply -f k8s/
```
