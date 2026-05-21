# Dockerized Node.js Express CI/CD Pipeline

A containerized Node.js/Express application featuring an automated CI/CD deployment pipeline built with GitHub Actions and Watchtower.

## 🚀 Features



- Automated CI: GitHub Actions workflow automatically builds a Docker image on every push to the `main` branch.

- Docker Hub Integration: Built images are securely pushed to Docker Hub registry using GitHub Secrets.

- Continuous Deployment (CD): Integrated with Watchtower to automatically pull the latest image and restart the container locally.

- Container Isolation: Ports and service configurations managed via Docker Compose.


## 🛠️ How to Run Locally



1. Clone the repository.

2. Ensure Docker Desktop is running.

3. Start the application using Docker Compose:


```bash

docker compose up
```

The application will be accessible at ```bash http://localhost:8080 ```

## 🌐 Live Deployment
The application is automatically deployed to Render and can be accessed live here:
- Live App: [https://express-pipeline-cloud.onrender.com](https://express-pipeline-cloud.onrender.com)



