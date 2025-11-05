# Next.js Application with CI/CD, Docker, and Kubernetes Deployment

This project demonstrates a complete CI/CD workflow using **GitHub Actions**, **Docker Hub**, and **Kubernetes (Kind cluster)**.

---

## 🚀 Project Overview

- **App Framework:** Next.js  
- **CI/CD Tool:** GitHub Actions  
- **Container Registry:** Docker Hub  
- **Deployment:** Kubernetes (Kind Cluster / EC2)  

The CI pipeline automatically builds and pushes a Docker image to Docker Hub whenever a change is pushed to the `main` branch.

---

## ⚙️ Setup Instructions

### 1️⃣ Fork the Repository

Fork this repository into your own GitHub account.

---

### 2️⃣ Set Secrets in GitHub

Go to your forked repository →  
**Settings → Secrets and variables → Actions → New repository secret**

Add the following secrets:

| Name | Example Value | Description |
|------|----------------|-------------|
| `DOCKERHUB_USERNAME` | `rakib770` | Your Docker Hub username |
| `DOCKERHUB_TOKEN` | `************` | Your Docker Hub access token |
| `IMAGE_NAME` | `rakib770/next-japan` | Full image name including repository |

---

### 3️⃣ Push the CI Workflow

Make sure your workflow file exists at: .github/workflows/ci.yml.


