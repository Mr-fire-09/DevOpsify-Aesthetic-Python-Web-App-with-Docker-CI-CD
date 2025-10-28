<!-- 🌸 Aesthetic DevOps Project README 🌸 -->

<div align="center">

# 🐳 DevOpsify  
### *A Beautiful Python Web App Built with Docker + Automated CI/CD Pipeline*

![Docker](https://img.shields.io/badge/Docker-Automated-blue?logo=docker&style=flat-square)
![Python](https://img.shields.io/badge/Python-3.11-yellow?logo=python&style=flat-square)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask&style=flat-square)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue?logo=githubactions&style=flat-square)

</div>

---

## 🌈 Overview

**DevOpsify** is a minimal yet aesthetic Python web application powered by **Flask**, containerized using **Docker**, and automated with a **GitHub Actions CI/CD pipeline** that builds and pushes the Docker image to Docker Hub seamlessly.

It’s perfect for **beginners exploring DevOps** or **students building a full automation demo**.  

---

## 🧱 Project Architecture

DevOpsify/
│
├── app.py
├── templates/
│ └── index.html
├── requirements.txt
├── Dockerfile
├── .github/
│ └── workflows/
│ └── docker-ci.yml
└── README.md


---

## 🎨 UI Preview

<div align="center">
  <img src="https://i.imgur.com/JZ7D7Fc.gif" width="600" alt="Aesthetic Flask App Preview">
</div>

---

## 🚀 Features

✅ Lightweight Flask backend  
✅ Beautiful responsive UI  
✅ Dockerized deployment (`localhost:5000`)  
✅ Automated build & push to Docker Hub  
✅ CI/CD using GitHub Actions  
✅ Beginner-friendly & production-ready  

---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/DevOpsify.git
cd DevOpsify

2️⃣ Build Docker Image
docker build -t devopsify-app .

3️⃣ Run the Container
docker run -p 5000:5000 devopsify-app

🧑‍💻 Author

👋 Neeraj Singh
💼 CS Student | DevOps & Cloud Enthusiast
🔗 LinkedIn
 • GitHub
 • Docker Hub

🌟 Show Your Support

If you like this project, please ⭐ the repo and share it!
Your support motivates continued learning and innovation 💙

💫 Technologies Used
Tool	Purpose
🐍 Python 3.11	Application logic
⚡ Flask	Lightweight web framework
🐳 Docker	Containerization
⚙️ GitHub Actions	CI/CD pipeline
💻 HTML + CSS	Frontend design
