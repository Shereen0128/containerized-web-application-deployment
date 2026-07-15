# Containerized Web Application Deployment 🚀

A static web application deployed using Docker and Nginx.

## 📌 Project Overview
This project demonstrates containerizing a web application using Docker. The application runs inside an Nginx container and is deployed using Docker commands.

## 🛠 Technologies Used
- Docker
- Nginx
- HTML
- CSS

## ⚙️ How to Run
### Build Docker Image
````md
docker build -t my-first-app .
```
### Run Docker Container
```bash
docker run -d -p 8080:80 --name my-container my-first-app
```

### Open Application
http://localhost:8080
