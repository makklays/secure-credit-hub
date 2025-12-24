# 🏦 Secure Credit Hub
Project has created from several microservices in Docker containers

Secure Credit Hub is a distributed system built using a microservices architecture, designed to provide secure and scalable financial services.
The project consists of multiple independent microservices, each running in its own Docker container and responsible for a specific business capability.

The system follows modern backend development practices, including service isolation, security, and observability.

# 🧩 Architecture Overview
The application is composed of several microservices that communicate with each other over secure APIs.

### Consist of next microservices:

<a href="#" target="_blank" >OAuth2 microservice</a> 

Responsible for authentication and authorization.

Provides secure access to system resources using OAuth2 standards and token-based security.

<a href="#" target="_blank" >Credit Cards microservice</a> 

Manages credit card data and related business logic, including card lifecycle and validation.

<a href="#" target="_blank" >Currency microservice</a> 

Handles currency data, exchange rates, and currency-related operations used across the system.

<a href="#" target="_blank" >Monitoring microservice</a> 

Provides observability features such as health checks, metrics collection, and service monitoring.

Other Supporting Microservices

Additional services can be added to extend system functionality and maintain scalability.

# 🐳 Containerization

All microservices are packaged and deployed as Docker containers, ensuring:

- Consistent environments

- Easy local development

- Simplified deployment and scaling 

# 🎯 Project Goals

- Demonstrate a real-world microservices architecture

- Implement secure communication between services

- Apply separation of concerns and clean service boundaries

- Enable easy scalability and observability

# 🛠️ Tech Stack

### Backend

Java — primary programming language

Spring Boot — building standalone, production-ready microservices

Spring Security — authentication and authorization

OAuth2 / OpenID Connect — secure token-based access control

Spring Cloud — service communication and configuration (where applicable)

### Containerization & Deployment

Docker — containerization of all microservices

Docker Compose — local orchestration of multiple services

(Optional) Kubernetes — container orchestration and scalability

### Data & Persistence

MySQL — relational database for persistent storage

JPA / Hibernate — object-relational mapping

Flyway — database versioning and migrations

Observability & Monitoring

Spring Boot Actuator — health checks and metrics

Monitoring Microservice — centralized monitoring and system observability

(Optional) Prometheus / Grafana — metrics collection and visualization

### Security

OAuth2 Authorization Server — centralized authentication service

JWT — stateless authentication tokens

HTTPS / Secure APIs — secure inter-service communication

### Development & Testing

Maven — dependency management and build tool

JUnit / Mockito — unit and integration testing

Testcontainers — container-based testing for external dependencies

