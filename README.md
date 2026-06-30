# 🚀 Node.js Todo Application Deployment using Docker, Amazon ECR & Amazon ECS (Fargate)

## 📌 Project Overview

This project demonstrates how to containerize a Node.js Todo application using Docker, store the Docker image in Amazon Elastic Container Registry (ECR), and deploy it on Amazon Elastic Container Service (ECS) using AWS Fargate.

The project showcases containerization, cloud deployment, IAM configuration, and centralized logging using Amazon CloudWatch.

---

## 🏗️ Architecture

```
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Docker Build
    │
    ▼
Amazon ECR
    │
    ▼
Amazon ECS (Fargate)
    │
    ▼
Running Container
    │
    ▼
Amazon CloudWatch Logs
```

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- Docker
- Amazon ECR
- Amazon ECS (Fargate)
- AWS IAM
- Amazon CloudWatch
- Git
- GitHub

---

## ✨ Features

- Dockerized Node.js Todo application
- Built Docker image using Dockerfile
- Stored container image in Amazon ECR
- Deployed the container using Amazon ECS (Fargate)
- Configured IAM Task Execution Role
- Integrated Amazon CloudWatch Logs for monitoring

---

## 📂 Project Structure

```
node-todo-aws-ecs/
│── app.js
│── Dockerfile
│── package.json
│── package-lock.json
│── views/
│── README.md
```

---

## 🚀 Deployment Workflow

1. Clone the repository.
2. Build the Docker image.
3. Create an Amazon ECR repository.
4. Authenticate Docker with Amazon ECR.
5. Push the Docker image to Amazon ECR.
6. Create an Amazon ECS Cluster.
7. Create an ECS Task Definition.
8. Run the task using AWS Fargate.
9. Monitor container logs using Amazon CloudWatch.

---

## 📸 Screenshots

Add your screenshots here.

- Docker Image Build
- Amazon ECR Repository
- Amazon ECS Cluster
- ECS Task Definition
- Running ECS Task
- CloudWatch Logs

---

## 📚 Learning Outcomes

- Learned Docker containerization.
- Worked with Amazon Elastic Container Registry (ECR).
- Deployed containers using Amazon ECS (Fargate).
- Configured IAM roles for ECS tasks.
- Used Amazon CloudWatch for container logging.

---

## 🚀 Future Improvements

- Add CI/CD using GitHub Actions or Jenkins.
- Deploy behind an Application Load Balancer.
- Provision infrastructure using Terraform.
- Add a custom domain with HTTPS.

---

## 👨‍💻 Author

**Abhinav Pittala**

- GitHub: https://github.com/abhinav150487
- LinkedIn: https://www.linkedin.com/in/abhinav-pittala-b43235377/
