# 📓 MindScribe 🧠✍️  
### Production-Ready Journaling Platform Backend

<!-- Banner -->
<div align="center">
  <img src="https://picsum.photos/1200/300" alt="MindScribe Banner" width="100%"/>
</div>

<p align="center">
<strong>MindScribe</strong> is a <strong>production-grade backend system</strong> for a modern journaling and self-reflection platform.  
Designed with <strong>scalability</strong>, <strong>security</strong>, and <strong>clean architecture</strong> using <strong>Spring Boot</strong>, <strong>MongoDB</strong>, and <strong>Apache Kafka</strong>.
</p>

---

<div align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=spring"/>
  <img src="https://img.shields.io/badge/Database-MongoDB-blue?style=for-the-badge&logo=mongodb"/>
  <img src="https://img.shields.io/badge/Messaging-Kafka-black?style=for-the-badge&logo=apachekafka"/>
  <img src="https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge"/>
</div>

---

## 👀 Why Recruiters Should Care

This project demonstrates real-world backend engineering skills:

- Secure authentication & authorization
- Event-driven architecture using Kafka
- Scheduled background processing
- Clean domain modeling
- Production-ready configuration
- API documentation & testing readiness

---

## 🚀 Overview

MindScribe is a fully functional, production-ready backend designed to power a rich journaling experience.  
It provides secure user authentication, complete CRUD operations for journal entries, a public community feed, and an automated weekly emotional & sentiment analysis system.

Kafka is used to decouple core business logic from asynchronous workflows such as summary generation and email notifications.

---

## ✨ Key Features

- 🔐 **Secure Authentication** — JWT-based authentication with role-based access (`USER`, `ADMIN`)
- ✍️ **Journal Management** — Create, update, delete, and fetch private/public journal entries
- 🏷️ **Tagging & Search** — Filter entries by tags, date ranges, mood, and sentiment
- 🌐 **Public Community Feed** — Optional sharing with engagement features
- 🧠 **Weekly Emotional Insights**
  - Average mood
  - Dominant mood
  - Average sentiment
  - Dominant sentiment
- 📨 **Kafka-Driven Notifications** — Weekly summaries published and consumed asynchronously
- 👮 **Admin Capabilities** — User moderation and system maintenance
- 📖 **API Documentation** — Swagger UI / OpenAPI via SpringDoc

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Language | Java 17 |
| Framework | Spring Boot 3 |
| Database | MongoDB |
| Messaging | Apache Kafka |
| Security | Spring Security, JWT |
| Build Tool | Maven |
| API Docs | SpringDoc OpenAPI |

---

## 🧭 Architecture Highlights

- Layered architecture with clear separation of concerns
- Event-driven design using Kafka
- Scheduler-based background jobs using Spring `@Scheduled`
- Enum-based domain modeling for moods, sentiments, and roles
- Index-aware MongoDB queries for performance
- Environment-based configuration for production readiness

---

## 🏁 Getting Started

```bash
git clone https://github.com/your-username/mindscribe.git
cd mindscribe
mvn clean install
mvn spring-boot:run
````

Application runs on `http://localhost:8080`

---

## 📖 API Documentation

* Swagger UI: `http://localhost:8080/swagger-ui/index.html`
* OpenAPI Spec: `http://localhost:8080/v3/api-docs`

---

## 🧪 Testing & Quality

* Unit tests via Maven (`mvn test`)
* Integration-test friendly (MongoDB & Kafka supported)
* Enums stored as strings for backward compatibility
* Secrets externalized from source control

---

## 🧩 Project Structure

```
src/main/java
 └── net.mindscribe
     ├── config
     ├── controller
     ├── dto
     ├── entity
     ├── enums
     ├── repository
     ├── scheduler
     └── service
```

---

## 🌱 Roadmap

* Web frontend (React / Next.js)
* Mobile application
* Microservices decomposition
* GenAI-powered journaling insights
* Recommendation engine

---

## 📝 License

MIT License

---

## 👨‍💻 Maintainer

**Manish Kumar Singh**
📧 [manishksingh.mnnit@gmail.com](mailto:manishksingh.mnnit@gmail.com)

---

⭐ **Recruiter Note:**
This repository showcases production-grade backend engineering, clean architecture, and event-driven system design rather than a toy or tutorial project.
