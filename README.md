# 🚀 Dockerize a React Application with Multi-Stage Build

## 📌 Objective
Learn how to create a **production-ready Docker image** for a React application using a **multi-stage Docker build**.  
This approach reduces image size, separates build dependencies from runtime, and prepares your app for deployment.

---

## 🧩 Project Overview

This project demonstrates how to:

1. Build a simple React application using **Create React App** structure.
2. Use a **Node.js stage** to install dependencies and compile the app.
3. Use an **NGINX stage** to serve the built static files.
4. Use a `.dockerignore` file to exclude unnecessary files.
5. Run and verify the React app using Docker.

---

## 🏗️ Folder Structure

react-docker-multistage/
│
├── Dockerfile
├── .dockerignore
├── package.json
├── public/
│ └── index.html
└── src/
├── App.js
└── index.js
