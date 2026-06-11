# Stock Pipeline Infrastructure

This repository manages the automated CI/CD pipeline and deployment architecture for the Full-Stack Product Catalog application.

## 🚀 Deployment Pipeline
This infrastructure uses GitHub Actions to automate the building and deployment of the microservices architecture.

- **Continuous Integration:** Automatically triggers on every push to the `main` branch.
- **Dockerization:** Builds multi-architecture (Linux/amd64) images for deployment compatibility.
- **Continuous Deployment:** Seamlessly triggers service redeployments to Render using Webhooks.
- **Security:** Implements robust secret management via GitHub Secrets to protect environment variables and API keys.

## 🛠 Tech Stack
- **CI/CD:** GitHub Actions
- **Containerization:** Docker, Docker Buildx
- **Cloud Hosting:** Render (PaaS)
