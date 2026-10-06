# Identity Service

A production-grade Identity and Access Management (IAM) service built with Spring Boot 3 as part of a modern monolithic architecture series. This module handles core security features including authentication, role-based authorization, and token management.

---

## Key Features

* **Authentication & Authorization:** Secure login/signup using JWT (JSON Web Tokens), Spring Security architecture, and BCrypt password hashing.
* **Role-Based Access Control (RBAC):** Fine-grained permission handling using method security (`@PreAuthorize`, `@PostAuthorize`).
* **Token Lifecycle Management:** Secure handling of token issuance, verification, logout, and Refresh Token flows aligned with OAuth2 behavior.
* **Advanced Validation & Exception Handling:** Custom validation annotations and centralized global exception handling with custom HTTP status codes.
* **Object Mapping & Code Quality:** Boilerplate reduction using Lombok and high-performance bean mapping with MapStruct. Enforced code styling with Spotless and static analysis integration.
* **Testing & Containerization:** Unit tests, integration testing with Testcontainers, containerized via Docker, and deployment-ready for AWS EC2.

---

## Tech Stack

* **Core:** Java 21, Spring Boot 3
* **Security:** Spring Security, JJWT (JWT)
* **Data Access:** Spring Data JPA, Hibernate, MySQL
* **Utilities:** MapStruct, Hibernate Validator, Lombok
* **Testing:** JUnit, Testcontainers
* **DevOps & Quality:** Docker, Spotless, SonarQube, AWS (EC2, Docker Hub)

---
