# 🏋️ Fitness App - Microservices Architecture

## 📌 Overview

This project is a **Fitness Application built using Microservices Architecture**. It allows users to manage workouts, track fitness activities, and interact with multiple backend services designed for scalability and modularity.

---

## 🚀 Features

* 🧑 User Registration & Authentication (JWT-based)
* 🏃 Workout Tracking & Management
* 📊 Fitness Data Monitoring
* 🔐 Secure REST APIs
* ⚡ Scalable Microservices-based backend
* 🔄 Inter-service communication

---

## 🧱 Architecture

This project follows a **Microservices Architecture**, where each service is independently deployable.

### 🔹 Services Included:

* **User Service** – Handles user registration & authentication
* **Workout Service** – Manages workout data
* **API Gateway** – Routes client requests
* **Service Registry (Eureka)** – Service discovery
* **Config Server** – Centralized configuration

---

## 🛠️ Tech Stack

### 🔹 Backend:

* Java
* Spring Boot
* Spring Cloud
* Spring Security (JWT)

### 🔹 Database:

* MySQL

### 🔹 Tools & Technologies:

* Docker
* Maven
* Postman
* Git

---

## 📡 API Endpoints (Sample)

### 🔐 Auth APIs

* `POST /auth/register` – Register user
* `POST /auth/login` – Login user

### 🏋️ Workout APIs

* `GET /workouts` – Get all workouts
* `POST /workouts` – Add workout

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/fitness-app-microservices-main.git
cd fitness-app-microservices-main
```

### 2️⃣ Configure Database

* Update MySQL credentials in `application.properties`

### 3️⃣ Run Services

Start services in this order:

1. Config Server
2. Eureka Server
3. API Gateway
4. Other Microservices

### 4️⃣ Access APIs

Use Postman or browser:

```
http://localhost:8080
```

---

## 📊 Key Highlights

* Built **10+ REST APIs** across multiple services
* Implemented **JWT-based authentication** for secure access
* Designed scalable backend using **microservices architecture**
* Structured services for **independent deployment and scaling**

---

## 📸 Future Improvements

* Add frontend dashboard
* Implement role-based access control
* Add monitoring (Prometheus/Grafana)
* Deploy on cloud (AWS/Azure)

---

## 🤝 Contribution

Feel free to fork this repository and contribute.

---

## 📧 Contact

**Suraj Sahil**
📩 [sahilsuraj05@gmail.com](mailto:sahilsuraj05@gmail.com)
