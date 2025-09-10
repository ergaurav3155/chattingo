# 💬 Chattingo — Real-time Chat Application  

[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)  
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)](https://www.jenkins.io/)  
[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://react.dev/)  
[![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)  
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)  

🚀 **Hackathon Project Submission** | Built with **React, Spring Boot, WebSocket, MySQL, Docker, and Jenkins CI/CD**.  
Chattingo delivers **secure, real-time messaging** in a **production-ready, containerized architecture**, deployable on a **VPS with Jenkins pipelines**.  

---

## 🎯 Problem Statement  

Most chat platforms are **either too heavy or lack DevOps readiness**. Hackathons demand apps that are **lightweight, scalable, and easy to deploy**.  

👉 **Chattingo** solves this by providing a **secure, modern, and deployable chat system** with real-time capabilities.  

---

## ✨ Features  

- 🔐 **JWT Authentication** → Secure signup/login  
- ⚡ **Real-time Messaging** → WebSocket (STOMP over SockJS)  
- 👥 **Private & Group Chats** → Multiple chat modes  
- 🎨 **Responsive UI** → Built with React + Tailwind CSS  
- 🐳 **Dockerized** → Fully containerized with Compose  
- 🔄 **Jenkins CI/CD** → Automated pipeline  
- 🌍 **Production-ready** → Nginx reverse proxy + SSL  

---

## 📸 Screenshots  

| Jenkins Pipeline | Chattingo Web | Sign Up Page |
|------------------|---------------|--------------|
| ![Jenkins Pipeline](./gaurav2.jpeg) | ![Chattingo Web](./gaurav3.jpeg) | ![Sign Up](./Gaurave1.jpeg) |

---

## 🛠️ Tech Stack  

- **Frontend:** React 18, Redux Toolkit, Tailwind CSS  
- **Backend:** Spring Boot 3, Spring Security, JPA  
- **Database:** MySQL  
- **Realtime:** WebSocket (SockJS + STOMP)  
- **DevOps:** Docker, Docker Compose, Jenkins, Nginx  
- **Hosting:** Linux VPS (Hostinger)  

---

## 🏗️ Architecture  

[ User Browser ]
|
v
[ React Frontend ] --> [ Nginx Reverse Proxy ] --> [ Spring Boot Backend ] --> [ MySQL DB ]
| |
+------ WebSocket / REST --------+

yaml
Copy code

---

## ▶️ Getting Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/ergaurav3155/chattingo/tree/main
cd chattingo
2️⃣ Setup Environment
bash
Copy code
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
3️⃣ Run with Docker Compose
bash
Copy code
docker-compose up --build -d
4️⃣ Access the App
Frontend → http://Ip-address:3000

Backend → http://Ip-Address:8080

📦 Useful Commands
bash
Copy code
# Start services
docker-compose up --build -d

# Stop and clean
docker-compose down -v

# Backend logs
docker-compose logs -f backend
🌍 Deployment Guide
🔹 Use docker-compose.prod.yml with pinned versions

🔹 Deploy on VPS with Nginx reverse proxy + SSL

🔹 Jenkins pipeline stages: Build → Scan → Push → Deploy

🔹 Store secrets in Docker secrets / environment manager

📂 Repository Structure
python
Copy code
chattingo/
├── backend/         # Spring Boot service
├── frontend/        # React + Tailwind UI
├── vars/            # Jenkins shared library
├── docker-compose.yml
├── Jenkinsfile
├── CONTRIBUTING.md
└── README.md
🏆 Hackathon Notes
✅ Built for fast prototyping + production readiness

✅ Implements DevOps best practices

✅ Ready for live VPS demo with SSL

✅ Showcases full-stack + CI/CD integration

👨‍💻 Contributing
Pull requests welcome!
For major changes, please open an issue first.
See CONTRIBUTING.md for more.

📜 License
Open-source project — free to use, improve, and share.

✨ Built with ❤️ during a Hackathon to showcase modern full-stack engineering + DevOps excellence.

yaml
Copy code

---

Would you like me to also **add a Hackathon “Team Members” & “Challenge Statement” section** (like many hackathon submissions require), or keep it strictly technical?







Ask ChatGPT
