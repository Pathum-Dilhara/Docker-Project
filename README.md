# 🚀 MERN Stack Application with Docker & Docker Compose

A full-stack **MERN** (MongoDB, Express.js, React, Node.js) application containerized using **Docker** and orchestrated with **Docker Compose**.  
This setup ensures a consistent development environment and makes deployment easier.

## 📂 Project Structure
```
project-root/
│
├── backend/ # Node.js + Express API
├── frontend/ # React app
├── docker-compose.yml
├── Dockerfile # (For backend or separate frontend Dockerfile)
└── README.md
```
## 📦 Build and start containers
```
docker-compose up --build
```

## 📍 Access the application

  - Frontend: http://localhost:3000
  - Backend API: http://localhost:5000
  - MongoDB: localhost:27017

## 📄 License

This project is licensed under the MIT License.
