# 🚀 DevOps CI/CD Project

## 📌 Overview
This project demonstrates a complete CI/CD pipeline using:
- Python Flask Application
- Docker
- GitHub Actions
- DockerHub

## 🛠 Tools Used
- Python
- Flask
- Docker
- GitHub Actions

## 🔄 CI/CD Workflow
1. Developer pushes code to GitHub
2. GitHub Actions triggers pipeline
3. Docker image builds automatically
4. Image pushes to DockerHub

## ▶ Run Locally

### Build Image
docker build -t devops-app .

### Run Container
docker run -p 5000:5000 devops-app

Open: http://localhost:5000

## 📦 DockerHub Image
Replace with your DockerHub link here.
