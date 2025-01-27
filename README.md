# 🏀 Game Day Schedule API  

Welcome to the **Game Day Schedule API**, a containerized sports application that provides real-time schedules and updates for game days. This project was built as part of a DevOps Challenge, showcasing how AWS services can be utilized to deploy and scale modern APIs with reliability and high availability.

---

## 🖥️ **Architecture Overview**

![Architecture Diagram](https://github.com/ifeanyiro9/containerized-sports-api/blob/main/architecture.png)

The architecture is built using the following components:

1. **API Gateway**: Manages incoming requests and routes them securely to the backend.
2. **Elastic Load Balancer (ALB)**: Distributes traffic evenly across multiple instances of the Sports API.
3. **Amazon ECS**: Orchestrates Docker containers running the Sports API.
4. **SERP API Backend**: Fetches real-time sports data and serves it to users.
5. **IAM Roles and Policies**: Ensures secure access between services with least privilege principles.

---

## 🚀 **Key Features**

- **Scalable Architecture**: Built on ECS with automatic load balancing for high availability.
- **Real-Time Data**: Integrates with external APIs to fetch live game schedules and updates.
- **Secure API Access**: Uses API Gateway for controlled access to endpoints.
- **Cost Efficiency**: Leveraged AWS services to minimize operational costs.

---

## ⚙️ **Tech Stack**

- **AWS Services**: API Gateway, Elastic Load Balancer, Amazon ECS.
- **Docker**: Containerized API for portability and efficiency.
- **Backend API**: Fetches data from external sports APIs for real-time updates.
- **Programming Language**: Python (Flask framework).

---

## 🛠️ **Setup Instructions**

Follow these steps to deploy the project locally or on AWS:

### **1. Clone the Repository**
```bash
git clone https://github.com/GilbertDaniel/30days-containerized-sports-api.git
cd containerized-sports-api
