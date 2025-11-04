# bookstore-microservices-on-aws-using-kops
Bookstore Microservices on AWS using Kops, Kubernetes, Helm, and Docker
This project showcases a complete microservices-based Bookstore application deployed on Kubernetes (created via Kops) on AWS EC2 instances.
It uses Helm for deployment, DockerHub for container images, and AWS Classic LoadBalancer for public access.
The app includes frontend, backend, and MySQL database microservices, with additional components like a CronJob for database backup and Node Exporter for monitoring.
# 📚 Bookstore Microservices on AWS using Kops and Kubernetes

## 🚀 Overview
This project demonstrates a **microservice-based Bookstore Application** deployed on **Kubernetes (via Kops)** using **Helm and Docker** on **AWS EC2 instances**.

It includes:
- **Frontend:** Spring Boot application (Dockerized)
- **Backend:** Spring Boot REST API (Dockerized)
- **Database:** MySQL StatefulSet
- **CronJob:** Automated database backup
- **Node Exporter:** System metrics collection

---

## 🏗️ Architecture
- **Kops** → Creates and manages the Kubernetes cluster on AWS
- **Kubernetes** → Orchestrates containers
- **Helm** → Manages deployment as reusable charts
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4620838c-d72b-4ed2-9fa6-351212c29da0" />

- **DockerHub** → Hosts container images
- **AWS LoadBalancer (Classic ELB)** → Exposes frontend publicly
- **EC2 instances** → Run the control plane and worker nodes

---
