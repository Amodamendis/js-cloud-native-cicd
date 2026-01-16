# Cloud-Native CI/CD Pipeline Project

### 🚀 Project Overview
This project demonstrates a fully automated DevOps pipeline for a Node.js application. It implements **Continuous Integration (CI)** using GitHub Actions and **Continuous Delivery (CD)** using Tekton on OpenShift.

### 🛠️ Tech Stack
* **Application:** Node.js (Express)
* **CI:** GitHub Actions (Linting & Unit Testing)
* **CD:** Tekton (OpenShift Pipelines)
* **Containerization:** Buildah & Docker
* **Orchestration:** Kubernetes / OpenShift

### 🔄 Workflow
1.  **Commit:** Code pushed to `main` triggers GitHub Actions.
2.  **Verify:** GitHub Actions runs `ESLint` and `Jest` tests.
3.  **Build:** Tekton pipeline clones code and builds a container image.
4.  **Deploy:** Image is deployed to the OpenShift cluster.

### 👨‍💻 Author
Built by **Amoda Rashmika mendis**