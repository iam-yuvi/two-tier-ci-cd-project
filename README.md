### 🔥 Two-Tier Flask + MySQL CI/CD Project (Docker + Jenkins)

This project showcases a two-tier application consisting of a **Flask web application** and a **MySQL database**, fully containerized and automated using **Jenkins CI/CD**.

---

### 🚀 Project Overview

- Flask handles both **frontend (HTML templates)** and **backend logic**
- MySQL provides persistent data storage
- Docker is used to containerize the entire application
- Docker Compose orchestrates multi-container deployment
- Jenkins Pipeline automates:
  - Pulling latest code from GitHub
  - Building updated Docker images
  - Re-deploying the application using Docker Compose

---

### 🧱 Architecture

Client (Browser) -> Flask App -> MySQL DB



Flask and MySQL run in separate containers connected through a Docker network, forming a clean two-tier architecture.

---

### 🛠 Technologies Used

- Flask (Python)
- MySQL
- Docker
- Docker Compose
- Jenkins Pipeline
- GitHub
- Linux

---

### 🚀 CI/CD Flow

1. Developer pushes code to **GitHub**
2. Jenkins pulls the new commit
3. Jenkins builds a fresh Docker image
4. Jenkins redeploys using Docker Compose
5. Updated application available instantly

---

### 🗂 Key Features

- Multi-container orchestration with Docker Compose  
- Persistent MySQL storage using Docker volumes  
- MySQL healthchecks to ensure DB readiness  
- Automatic application rebuilds using `--build`  
- End-to-end CI/CD using a declarative Jenkinsfile  

---

### 🎯 What I Learned

- Containerizing Python applications  
- Managing multi-container environments  
- Writing Jenkins pipelines for automated deployments  
- Using Docker networks & volumes  
- Connecting Flask apps to MySQL in containers  
- Deploying production-like environments locally  

---

If you like this project, feel free to ⭐ the repository!
