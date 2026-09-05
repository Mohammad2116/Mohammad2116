# 👋 Hi, I'm Mohammad Momen Safaei

### Senior Software Engineer · Backend Specialist · Java / Spring Boot

<p align="left">
  <a href="https://www.aspireapps.ir"><img src="https://img.shields.io/badge/Website-aspireapps.ir-blue?style=flat-square&logo=google-chrome&logoColor=white" /></a>
  <a href="mailto:mohammad2116@gmail.com"><img src="https://img.shields.io/badge/Email-mohammad2116%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Mohammad2116"><img src="https://img.shields.io/badge/GitHub-Mohammad2116-black?style=flat-square&logo=github&logoColor=white" /></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-316192?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-8-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-Event_Driven-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

> **Backend engineer focused on Java, Spring Boot, security, distributed systems, and production-minded architecture.**
>
> Open to **Senior Backend / Java / Spring Boot** opportunities, including remote roles.

---

## 🚀 About Me

I’m a backend-focused software engineer with **15+ years of experience** across software development, game development, technical leadership, and computer science education.

Today, I focus on building **secure, scalable, maintainable backend systems** with Java and Spring Boot. I’m especially interested in the engineering problems behind production systems: service boundaries, authentication, data consistency, caching, asynchronous processing, failure handling, and deployment.

I believe good backend engineering is not just about making an API work — it is about making the system **reliable, understandable, secure, and ready to evolve**.

---

## 🧠 Core Engineering Skills

- 🏗️ **Backend Architecture** — layered architecture, modular design, microservices, service boundaries
- 🔐 **Security** — Spring Security, JWT, access/refresh tokens, RBAC, token rotation & revocation
- ⚡ **Performance** — Redis, cache-aside patterns, TTL strategies, database optimization
- 🔄 **Distributed Systems** — Kafka, asynchronous processing, service discovery, transactional Outbox
- 🗄️ **Persistence** — PostgreSQL, JPA/Hibernate, transactions, Flyway migrations
- 🌐 **API Development** — REST, OpenAPI/Swagger, DTOs, validation, OpenFeign
- 🚀 **DevOps** — Docker, Docker Compose, GitHub Actions, Linux, Caddy, Cloudflare

---

# ⭐ Featured Project: AspireApps Linker

### Production-oriented distributed URL shortener

[**AspireApps Linker**](https://github.com/Mohammad2116/AspireApps_Linker) is my main backend portfolio project — a Java/Spring Boot microservices system built to demonstrate practical distributed-system engineering rather than a simple CRUD application.

### What it demonstrates

| Area | Implementation |
| :--- | :--- |
| **Architecture** | Spring Boot microservices + clear service boundaries |
| **Gateway** | Spring Cloud Gateway |
| **Discovery** | Netflix Eureka |
| **Authentication** | Spring Security + JWT access/refresh tokens |
| **Token Security** | Persistent hashed refresh tokens, rotation & revocation |
| **Caching** | Redis cache-aside + popularity-aware TTL |
| **Messaging** | Apache Kafka + asynchronous analytics |
| **Reliability** | Transactional Outbox Pattern |
| **Persistence** | PostgreSQL + JPA/Hibernate |
| **Migrations** | Flyway |
| **Service Calls** | OpenFeign |
| **Deployment** | Docker Compose + GitHub Actions + GHCR |
| **Edge / Routing** | Caddy + Cloudflare |

### High-level architecture

```text
                         ┌──────────────────────┐
                         │       Clients        │
                         │ Browser / REST API   │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │   Caddy / Cloudflare │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │   Spring Cloud       │
                         │       Gateway        │
                         └──────┬───────┬───────┘
                                │       │
                  ┌─────────────┘       └─────────────┐
                  ▼                                   ▼
          ┌──────────────┐                    ┌──────────────┐
          │ User Service │                    │ Links Service│
          │ Auth / Users │                    │ Links / Redis│
          └───────┬──────┘                    └───────┬──────┘
                  │                                   │
                  └────────────────┬──────────────────┘
                                   │
                            ┌──────▼──────┐
                            │   Eureka    │
                            │  Discovery  │
                            └─────────────┘

                         ┌────────────────┐
                         │     Kafka      │
                         │ Async Events   │
                         └───────┬────────┘
                                 ▼
                         ┌───────────────┐
                         │    Analysis   │
                         │    Service    │
                         └───────┬───────┘
                                 ▼
                         ┌───────────────┐
                         │  PostgreSQL   │
                         └───────────────┘
```

### Live project

- 🌐 **Web:** [aspireapps.ir/linker](https://aspireapps.ir/linker/home)
- 🔌 **API:** [api.aspireapps.ir/linker](https://api.aspireapps.ir/linker)
- 💻 **Source:** [GitHub Repository](https://github.com/Mohammad2116/AspireApps_Linker)

---

## 🛠️ Technology Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | Java, C++, C#, Python, JavaScript, SQL |
| **Backend** | Spring Boot, Spring MVC, Spring Data JPA, Hibernate, Thymeleaf |
| **Security** | Spring Security, JWT, BCrypt, RBAC |
| **Distributed Systems** | Spring Cloud Gateway, Eureka, OpenFeign, Kafka, Outbox Pattern |
| **Data** | PostgreSQL, Redis, Flyway |
| **API** | REST, OpenAPI, Swagger, DTOs, MapStruct |
| **DevOps** | Docker, Docker Compose, GitHub Actions, Maven, Linux, Caddy, Cloudflare |
| **Development** | Git, IntelliJ IDEA, CI/CD |

---

## 📌 Selected Projects

### 🛒 SpringMart — E-Commerce Backend

A production-oriented Spring Boot REST API demonstrating authentication, authorization, persistence, caching, API documentation, database migrations, and automated deployment.

**Stack:** Java · Spring Boot · Spring Security · PostgreSQL · Redis · Docker · Flyway · Swagger

🔗 [Repository](https://github.com/Mohammad2116/springMart) · [Live API](https://springmart-backend-v2ux.onrender.com) · [Swagger](https://springmart-backend-v2ux.onrender.com/swagger-ui/index.html)

### 🔐 Spring JWT Auth Service

A dedicated authentication service focused on secure JWT access/refresh token handling, persistent token management, and clean security boundaries.

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

## 🎯 What I Bring to a Backend Team

- Strong software-development experience combined with formal teaching and mentoring experience
- Practical understanding of **authentication, authorization, caching, messaging, persistence, and distributed architecture**
- Comfortable working across application code, databases, containers, CI/CD, and Linux environments
- Strong interest in understanding **why** an architecture works, not only how to implement it
- Experience turning complex requirements into maintainable backend components and service boundaries

---

## 📊 GitHub Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohammad2116&show_icons=true&theme=tokyonight&count_private=true" alt="Mohammad's GitHub Stats" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohammad2116&layout=compact&theme=tokyonight" alt="Top Languages" height="160"/>
</p>

---

## 📫 Contact

- 🌐 **Website:** [aspireapps.ir](https://aspireapps.ir)
- 📧 **Email:** [mohammad2116@gmail.com](mailto:mohammad2116@gmail.com)
- 📍 **Location:** Iran · Open to remote opportunities globally
- 📄 [English Resume](https://github.com/Mohammad2116/Mohammad2116/blob/main/Prof%20Resume%20(En).pdf)
- 📄 [Persian Resume](https://github.com/Mohammad2116/Mohammad2116/blob/main/Prof%20Resume%20(Fa).pdf)

---

### ⚙️ Engineering Philosophy

> **Build systems that are secure by design, reliable under failure, efficient under load, and understandable six months after they were written.**

---

⭐ If you're interested in **Java, Spring Boot, backend engineering, or distributed systems**, feel free to explore my repositories.
