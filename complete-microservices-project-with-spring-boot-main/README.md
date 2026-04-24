# Complete Microservices Project with Spring Boot





 
# 🏦 Banking Microservice Observability Platform


## 📸 Dashboard Preview

Below is the observability dashboard showing real-time system metrics:

![Grafana Dashboard](docs/dashboard.png)


## 🚀 Overview

The **Banking Microservice Observability Platform** is a distributed banking system built using **Spring Boot and Spring Cloud**, designed to demonstrate real-world **microservices architecture** along with a complete **observability stack**.

This project focuses on how modern systems handle:

* Scalability through independent services
* Fault tolerance and resilience
* Monitoring, logging, and distributed tracing
* Containerized deployments

---

## 🏗️ System Architecture

The platform follows a **microservices-based architecture**, where each service is independently developed, deployed, and scaled.

### 🔹 Core Services

* **Account Service** → Manages customer accounts
* **Card Service** → Handles card operations
* **Loan Service** → Processes loan requests

### 🔹 Infrastructure Services

* **Config Server** → Centralized configuration management
* **Eureka Server** → Service discovery and registration

---

## 🔍 Observability Stack

A full observability pipeline is integrated into the system:

* **Prometheus** → Metrics collection
* **Grafana** → Real-time dashboards and visualization
* **Loki + Promtail** → Centralized logging
* **Tempo** → Distributed tracing across services

---

---

## ⚙️ Tech Stack

| Category         | Technologies         |
| ---------------- | -------------------- |
| Backend          | Java, Spring Boot    |
| Microservices    | Spring Cloud         |
| Messaging        | Kafka / RabbitMQ     |
| Resilience       | Resilience4j         |
| Containerization | Docker               |
| Orchestration    | Kubernetes (Planned) |
| Monitoring       | Prometheus, Grafana  |
| Logging          | Loki, Promtail       |
| Tracing          | Tempo                |

---

## 📂 Project Structure

```
Banking-Microservice-Observability-Platform/
│
├── account-management
├── card-management
├── loan-management
├── configserver
├── eurekaserver
├── lib-common
├── _docker-compose
└── docs/
    └── dashboard.png
```

---

## 🔄 Service Communication

The system supports:

* **Synchronous communication** using REST APIs
* **Asynchronous communication** using Kafka / RabbitMQ

---

## ▶️ Getting Started

### 1️⃣ Clone the Repository

```
git clone https://github.com/kishangithubkumar/Banking-Microservice-Observability-Platform.git
cd Banking-Microservice-Observability-Platform
```

---

### 2️⃣ Run with Docker

```
docker-compose up -d
```

---

### 3️⃣ Access Services

* Eureka Dashboard → http://localhost:8761
* Grafana Dashboard → http://localhost:3000
* Prometheus → http://localhost:9090

---

## 📊 Key Features

✔️ Microservices-based architecture
✔️ Service discovery using Eureka
✔️ Centralized configuration management
✔️ Real-time monitoring with Prometheus & Grafana
✔️ Centralized logging using Loki
✔️ Distributed tracing using Tempo
✔️ Docker-based deployment
✔️ Scalable and modular design

---

## 🧠 Learnings

* Designing distributed systems using microservices
* Implementing observability (metrics, logs, traces)
* Handling inter-service communication
* Monitoring system health in real time

---

## 🎯 Future Enhancements

* API Gateway (Spring Cloud Gateway)
* Authentication & Authorization (JWT / OAuth2)
* CI/CD pipeline (GitHub Actions)
* Kubernetes deployment
* Alerting system in Grafana

---

## 👨‍💻 Author

**Kishan Kumar**
GitHub: https://github.com/kishangithubkumar

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
