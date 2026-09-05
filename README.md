# 👋 Hi, I'm Mohammad Momen Safaei

### Senior Software Engineer · Backend Specialist · Java / Spring Boot

<p align="left">
  <a href="https://www.aspireapps.ir"><img src="https://img.shields.io/badge/Website-aspireapps.ir-blue?style=flat-square&logo=google-chrome&logoColor=white" /></a>
  <a href="mailto:mohammad2116@gmail.com"><img src="https://img.shields.io/badge/Email-mohammad2116%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Mohammad2116"><img src="https://img.shields.io/badge/GitHub-Mohammad2116-black?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

## 🚀 About Me

I’m a backend-focused software engineer with **15+ years of experience** across software development, game development, technical leadership, and computer science education.

My current focus is building **secure, scalable, and maintainable Java backend systems** with Spring Boot and distributed-system architecture. I enjoy going beyond simply making an API work — I care about **architecture, reliability, performance, security, observability, and clean engineering decisions**.

> **Current focus:** Java · Spring Boot · Distributed Systems · Microservices · Security · PostgreSQL · Redis · Kafka · Docker · CI/CD

---

## 🧠 Engineering Focus

- 🏗️ **Backend Architecture** — layered architecture, modular design, microservices, service discovery
- 🔐 **Security** — Spring Security, JWT access/refresh tokens, RBAC, token rotation and revocation
- ⚡ **Performance** — Redis caching, cache-aside patterns, popularity-aware TTL strategies
- 🔄 **Distributed Systems** — asynchronous processing, Kafka, transactional Outbox pattern
- 🗄️ **Data** — PostgreSQL, JPA/Hibernate, Flyway, transaction management
- 🚀 **DevOps** — Docker, Docker Compose, GitHub Actions, Linux, reverse proxies and cloud deployment
- 🧪 **API Engineering** — REST, OpenAPI/Swagger, DTO mapping, validation and resilient service boundaries

---

## ⭐ Featured Project — AspireApps Linker

### A production-style distributed URL shortener built to demonstrate real backend engineering

**AspireApps Linker** is a Java/Spring Boot microservices system designed around the kinds of architectural concerns found in production distributed applications.

**Architecture highlights:**

- 🔐 JWT-based authentication with access & refresh token lifecycle management
- 🧩 Spring Cloud Gateway + Eureka service discovery
- ⚡ Redis cache-aside strategy with popularity-aware expiration
- 📊 Kafka-based asynchronous analytics pipeline
- 📦 Transactional **Outbox Pattern** for reliable event publishing
- 🗃️ PostgreSQL with Flyway versioned migrations
- 🔗 OpenFeign for service-to-service communication
- 🐳 Docker Compose for reproducible environments
- 🔄 GitHub Actions CI/CD and container-based deployment
- 🌐 Separate web and REST API entry points behind a reverse proxy

**Request flow:**

```text
                    ┌──────────────────────┐
                    │       Client         │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Gateway / Caddy    │
                    └──────────┬───────────┘
                               │
                ┌──────────────┼──────────────┐
                ▼              ▼              ▼
          User Service   Links Service   Analysis Service
                │              │              │
                ▼              ▼              ▼
           PostgreSQL        Redis          Kafka
                │              │              │
                └──────────────┴──────┬───────┘
                                      ▼
                              Transactional Outbox
```

🔗 **Project:** [AspireApps_Linker](https://github.com/Mohammad2116/AspireApps_Linker)

---

## 🛠️ Technology Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | Java, C++, C#, Python, JavaScript, SQL |
| **Backend** | Spring Boot, Spring MVC, Spring Data JPA, Hibernate, Thymeleaf |
| **Security** | Spring Security, JWT, OAuth2 concepts, RBAC, session/cookie authentication |
| **Distributed Systems** | Spring Cloud Gateway, Eureka, OpenFeign, Kafka, Outbox Pattern |
| **Data & Caching** | PostgreSQL, Redis, Flyway |
| **API** | REST, OpenAPI, Swagger, DTOs, MapStruct |
| **DevOps** | Docker, Docker Compose, GitHub Actions, Maven, Linux, Caddy |
| **Development** | Git, IntelliJ IDEA, CI/CD, automated migrations |

---

## 📌 Other Projects

### 🛒 SpringMart — E-Commerce Backend

A production-oriented Spring Boot REST API demonstrating authentication, authorization, persistence, caching, API documentation, and automated deployment.

**Stack:** Java · Spring Boot · Spring Security · PostgreSQL · Redis · Docker · Flyway · Swagger

🔗 [Repository](https://github.com/Mohammad2116/springMart) · [Live API](https://springmart-backend-v2ux.onrender.com) · [Swagger](https://springmart-backend-v2ux.onrender.com/swagger-ui/index.html)

### 🔐 Spring JWT Auth Service

A dedicated authentication service focused on secure JWT access/refresh token handling, persistent token management, and clean service boundaries.

**Stack:** Java · Spring Boot · Spring Security · JWT · OpenAPI

🔗 [Repository](https://github.com/Mohammad2116/spring-jwt-auth-service)

### 📱 Spring Thymeleaf Phonebook

A server-rendered web application demonstrating secure sessions, persistent "Remember Me" authentication, pagination, search, and user-specific data access.

**Stack:** Spring Boot · Thymeleaf · Spring Security · PostgreSQL · Bootstrap

🔗 [Repository](https://github.com/Mohammad2116/spring-thymeleaf-phonebook)

---

## 💼 Career Snapshot

**Technical Lead & CEO — Neonica Game Studio** · 2021–2023  
Led technical architecture and cross-functional engineering teams while delivering commercial software projects.

**Unity Software Developer — PFAP** · 2017–2020  
Developed gameplay systems and technical infrastructure for multiple published commercial titles.

**Computer Science Instructor & IT Expert — Ministry of Education / TVTO** · 2006–2020  
More than a decade of teaching and mentoring in programming, software engineering, and information technology.

---

## 📊 GitHub Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohammad2116&show_icons=true&theme=tokyonight&count_private=true" alt="Mohammad's GitHub Stats" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohammad2116&layout=compact&theme=tokyonight" alt="Top Languages" height="160"/>
</p>

---

## 📫 Contact

- 🌐 **Website:** [aspireapps.ir](https://www.aspireapps.ir)
- 📧 **Email:** [mohammad2116@gmail.com](mailto:mohammad2116@gmail.com)
- 📍 **Location:** Iran · Open to remote opportunities globally
- 📄 [English Resume](https://github.com/Mohammad2116/Mohammad2116/blob/main/Prof%20Resume%20(En).pdf)
- 📄 [Persian Resume](https://github.com/Mohammad2116/Mohammad2116/blob/main/Prof%20Resume%20(Fa).pdf)

---

### ⚙️ What I Like Building

**Systems that are secure by design, fast under load, observable in production, and understandable six months after they were written.**

---

⭐ If you're interested in backend engineering, distributed systems, or Java/Spring architecture, feel free to explore the repositories above.
