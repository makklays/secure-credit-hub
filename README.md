# 🏦 Secure Credit Hub 
Project has created from several microservices in Docker containers

Secure Credit Hub is a distributed system built using a microservices architecture, designed to provide secure and scalable financial services.
The project consists of multiple independent microservices, each running in its own Docker container and responsible for a specific business capability.

The system follows modern backend development practices, including service isolation, security, and observability.

## ☕ About 

I created this project from scratch as a system composed of multiple microservices.

The main goal of this project was to work in the roles of <b>Software Architect</b> and <b>Team Lead</b>, designing and implementing a complete microservice-based system from the ground up. As an architect, I was responsible for justifying the architectural decisions and explaining why this particular architecture was chosen for the implementation. As a team lead, I focused on defining how the architecture should be implemented in practice and how the system should be developed according to the architectural vision. As a <b>Senior Java Software Engineer</b>, I implemented this project based on the requirements and architectural guidelines provided by the Software Architect and the Team Lead, applying my expertise in effective Java practices and clean code principles.

This project demonstrates both architectural thinking and hands-on implementation of a microservices system, including design decisions (microservices, clear architecture, DDD), technical trade-offs, and development practices.

This project demonstrating me as:
- Software Architect
- Team Lead
- Senior Java Software Engineer

## 🧩 Architecture Overview
The application is composed of several microservices that communicate with each other over secure APIs.

### Consist of next microservices:

<a href="#" target="_blank" >OAuth2 microservice</a> 

Responsible for authentication and authorization.

Provides secure access to system resources using OAuth2 standards and token-based security.

<a href="https://github.com/makklays/java-credit-cards-microservice" target="_blank" >Credit Cards microservice</a> 

Manages credit card data and related business logic, including card lifecycle and validation.
Handles currency data, exchange rates, and currency-related operations used across the system. Also for every credit card has loyalty points and an opportunity adding it.

<a href="#" target="_blank" >Monitoring microservice</a> 

Provides observability features such as health checks, metrics collection, and service monitoring.

Other Supporting Microservices

Additional services can be added to extend system functionality and maintain scalability.

## 🐳 Containerization

All microservices are packaged and deployed as Docker containers, ensuring:

- Consistent environments

- Easy local development

- Simplified deployment and scaling 

## 🎯 Project Goals

- Demonstrate a real-world microservices architecture

- Implement secure communication between services

- Apply separation of concerns and clean service boundaries

- Enable easy scalability and observability

## 🛠️ Tech Stack

### Backend

- Java — primary programming language

- Spring Boot — building standalone, production-ready microservices

- WebFlux — Spring Reactive  

- Spring Security — authentication and authorization

- OAuth2 / OpenID Connect — secure token-based access control

- Spring Cloud — service communication and configuration (where applicable)

### Containerization & Deployment

- Docker — containerization of all microservices

- Docker Compose — local orchestration of multiple services

- (Optional) Kubernetes — container orchestration and scalability

### Data & Persistence

- MySQL — relational database for persistent storage

- JPA / Hibernate — object-relational mapping

- Flyway — database versioning and migrations

- Observability & Monitoring

- Spring Boot Actuator — health checks and metrics

- Monitoring Microservice — centralized monitoring and system observability

- (Optional) Prometheus / Grafana — metrics collection and visualization

### Security

- OAuth2 Authorization Server — centralized authentication service

- JWT — stateless authentication tokens

- HTTPS / Secure APIs — secure inter-service communication

### Development & Testing

- Maven — dependency management and build tool

- JUnit / Mockito — unit and integration testing

- Testcontainers — container-based testing for external dependencies

