# Containerized Web Application Deployment 🚀

A static web application deployed using Docker and Nginx.

## 📌 Project Overview

This project demonstrates containerizing a web application using Docker. The application runs inside an Nginx container and is deployed using Docker commands.

## 🛠 Technologies Used

- Docker
- Nginx
- GitHub Actions
- HTML
- CSS

## ⚙️ How to Run

### Build Docker Image

```bash
docker build -t my-first-app .
```

### Run Docker Container

```bash
docker run -d -p 8080:80 --name my-container my-first-app
```

### Open Application

```
http://localhost:8080
```

---

## 🔄 GitHub Actions CI Pipeline

This project uses GitHub Actions for Continuous Integration.

The workflow automatically runs on every push to GitHub.

### Pipeline Steps

1. Checkout Repository
2. Build Docker Image
3. Verify Build Success

### Workflow File

```
.github/workflows/ci.yml
```