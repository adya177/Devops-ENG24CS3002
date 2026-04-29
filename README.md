# DevOps Project

## 📌 Description
This is a simple HTML project deployed using Docker.  
The application displays a basic webpage using an NGINX server inside a Docker container.

---

## 🛠️ Technologies Used
- HTML  
- Docker  
- NGINX  

---

## 🚀 Steps to Run the Project

### 1. Build Docker Image
```bash
docker build -t my-app .

docker run -p 8080:80 my-app

![Output](project.jpeg)