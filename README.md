# 🚀 Simple Node.js CI/CD Pipeline

A simple **Node.js web application** with a complete automated **CI/CD pipeline** using **GitHub Actions, Docker, and Docker Hub**.

Every time code is pushed to the `main` branch, GitHub Actions automatically runs tests, builds a Docker image, and pushes the image to Docker Hub.

---

## 🛠️ Tech Stack

- **Node.js & Express** — Web application
- **Node.js Test Runner & Supertest** — Automated testing
- **Docker** — Application containerization
- **GitHub** — Source code management
- **GitHub Actions** — CI/CD automation
- **Docker Hub** — Container image registry

---

## 🔄 CI/CD Workflow

```text
Developer Push
      ↓
   GitHub
      ↓
GitHub Actions
      ↓
 Run Automated Tests
      ↓
   Tests Pass?
      ↓
Build Docker Image
      ↓
Push Image to Docker Hub
