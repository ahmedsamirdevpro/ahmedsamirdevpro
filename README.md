<div align="center">

# Ahmed Samir AbdElhamid
### Java Backend Engineer | Spring Boot | Distributed Systems

</div>

---

## About Me

I'm a **Java Backend Engineer** focused on building reliable, scalable, and maintainable backend systems using **Java, Spring Boot, microservices, and distributed systems**.

I enjoy solving engineering problems involving **data consistency, concurrency, event-driven architecture, resilience, security, caching, testing, and observability**.

Currently, I work on backend services for a **medical B2B marketplace**, covering authentication, orders, payments, and search.

> **Ideas → Build → Deploy → Improve**

---

## Core Expertise

- Java & Spring Boot backend development
- RESTful APIs and distributed services
- Microservices & event-driven architecture
- Apache Kafka & RabbitMQ
- PostgreSQL, Redis & Hibernate/JPA
- Spring Security, JWT & OAuth2/OIDC
- Docker & Kubernetes
- JUnit, Mockito & Testcontainers
- Prometheus, Grafana & OpenTelemetry
- k6 performance testing
- Clean Code, SOLID & Design Patterns

---

## Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring%20MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI%2FSwagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### Architecture & Messaging

![Microservices](https://img.shields.io/badge/Microservices-1F2937?style=for-the-badge)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-6E56CF?style=for-the-badge)

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

### Security

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-3C5A99?style=for-the-badge)
![OIDC](https://img.shields.io/badge/OIDC-4472C4?style=for-the-badge)

### DevOps & Observability

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Testing & Performance

![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78C257?style=for-the-badge)
![Testcontainers](https://img.shields.io/badge/Testcontainers-4B5563?style=for-the-badge)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)

---

## Featured Projects

### 💳 E-Wallet & Payment Platform

A transaction-centric wallet and payment platform built with **Java 25 and Spring Boot**.

- Wallet management, deposits, withdrawals, peer-to-peer transfers, payments, refunds, webhooks, and reconciliation.
- ACID transactions, double-entry ledger accounting, idempotency keys, transaction isolation, atomic balance updates, and concurrency protection.
- Kafka events, Transactional Outbox, retry/circuit-breaker strategies, webhook deduplication, audit trails, scheduled reconciliation, Testcontainers, CI/CD, and k6 performance testing.

**Stack:** Java 25 · Spring Boot · Spring Security · PostgreSQL · Flyway · Redis · Kafka · Resilience4j · Docker · Prometheus · Grafana · OpenTelemetry · k6

---

### 🛒 E-Commerce Platform

A distributed e-commerce platform implemented with **Java 25 and Spring Boot microservices**.

- Product catalog, cart, inventory, checkout, order lifecycle, and payment workflows behind an API Gateway.
- Event-driven workflows using Kafka with Saga and Outbox patterns, idempotent consumers, resilience, caching, and concurrency controls.
- OAuth 2.1/OIDC security, Testcontainers, distributed observability, GitHub Actions CI/CD, and k6 load testing.

**Stack:** Java 25 · Spring Boot · Spring Web MVC · Spring Security · OAuth2 · Spring Cloud Gateway · PostgreSQL · Hibernate · Flyway · Redis · Kafka · Docker · AWS

---

### 🔗 URL Shortener

A production-oriented RESTful URL shortener built with **Java 25 and Spring Boot 4.1.1**.

- Implemented URL creation, 302 redirects, validation, centralized exception handling, and 7-character Base62 short-code generation with database uniqueness and bounded collision retries.
- Implemented Redis Cache-Aside with PostgreSQL as the source of truth, one-hour TTL, and graceful fallback when Redis is unavailable.
- Added Flyway migrations, GitHub Actions CI with PostgreSQL and Redis service containers, Docker multi-stage builds, Docker Compose, unit/integration testing, and OpenAPI/Swagger documentation.
- Load tested with k6, reaching approximately **5,000 local RPS** with a measured **P95 of ~5.39 ms** for the Redis cache-hit scenario.

**Stack:** Java 25 · Spring Boot · Spring Web MVC · Spring Data JPA · PostgreSQL · Hibernate · Flyway · Redis · JUnit · Mockito · Docker · GitHub Actions · k6

---

## Engineering Focus

```text
Scalable Backend Systems
        ↓
Distributed Systems
        ↓
Event-Driven Architecture
        ↓
Data Consistency & Concurrency
        ↓
Resilience & Fault Tolerance
        ↓
Security
        ↓
Testing & Performance
        ↓
Observability
```

I'm particularly interested in engineering systems that remain **correct, observable, resilient, and maintainable under real-world load and failure conditions**.

---

## Currently Learning & Exploring

- Advanced System Design
- Distributed Systems
- Event-Driven Architecture
- Cloud-Native Backend Engineering
- Spring AI
- RAG & MCP
- BPMN 2.0
- Camunda BPM & Workflow Automation

---

## Education

**B.Sc. Computer Science — Benha University, 2024**

Graduation Project: **Credit Card Fraud Detection using Machine Learning & Federated Learning** — Team Leader

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmed%20Samir-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmedsamir-devpro)
[![Gmail](https://img.shields.io/badge/Gmail-ahmedsamir.devpro-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedsamir.devpro@gmail.com)

</div>
