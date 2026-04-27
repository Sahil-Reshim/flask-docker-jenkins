# 🚀 CI/CD Pipeline for Flask App using Jenkins, Docker & AWS EC2

This project demonstrates a complete **CI/CD pipeline** to automate the deployment of a Flask application using modern DevOps tools.

The pipeline ensures that every code push to GitHub automatically builds, pushes, and deploys the application.

---

## 🔧 Tech Stack

- Flask (Backend Application)
- Jenkins (CI/CD Automation)
- Docker (Containerization)
- DockerHub (Image Registry)
- Gunicorn (Production WSGI Server)
- Nginx (Reverse Proxy - Port 80)
- AWS EC2 (Deployment Server)

---

## 🔄 CI/CD Workflow

GitHub Push
↓
GitHub Webhook Trigger
↓
Jenkins Pipeline Execution
↓
Docker Image Build
↓
DockerHub Push
↓
EC2 Container Deployment (Gunicorn)
↓
Nginx Reverse Proxy (Port 80)
↓
Live Application


---

## 📁 Project Structure


flask-docker-jenkins/

├── app.py

├── requirements.txt

├── Dockerfile

└── Jenkinsfile


---

## ⚙️ Jenkins Pipeline Stages

- Clone Code from GitHub
- Build Docker Image
- Login to DockerHub
- Push Image to DockerHub
- Remove Old Container
- Run New Container

---

## 🐳 Docker Image

Available on DockerHub:

sahilreshim/flask-docker-app:latest


---

## 🌐 Live Demo

⚠️ **Note:**

This project was deployed on AWS EC2 for demonstration purposes.

The EC2 instance is not running continuously, so the live application may not always be accessible.

---

## 🔗 Project Showcase

📌 Detailed explanation and workflow:

👉 https://www.linkedin.com/feed/update/urn:li:ugcPost:7454462311207075840/

---

## 🎯 Key Learnings

- Building end-to-end CI/CD pipelines
- Automating deployments using Jenkins
- Containerizing applications with Docker
- Managing DockerHub authentication using access tokens
- Using Gunicorn for production-ready apps
- Configuring Nginx as a reverse proxy
- Debugging real-world CI/CD issues

---

## 🚀 Future Improvements

- Add HTTPS using Nginx + Let's Encrypt
- Implement Docker Compose
- Deploy using Kubernetes
- Add monitoring (Prometheus + Grafana)

---

## 👨‍💻 Author

**Sahil Reshim**  
Cloud & DevOps Enthusiast  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
