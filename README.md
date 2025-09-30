Restaurant Management Platform — Gateway Service

Welcome to the Gateway Service repository, a core component of the Restaurant Management Platform — a microservices-based backend system for managing restaurant operations efficiently.

About the Project:

This platform enables restaurants to manage menus, process customer orders, and deliver real-time notifications. The system leverages event-driven architecture with Apache Kafka to ensure scalable and reliable communication between services.

Gateway Service Overview:

The Gateway Service serves as the API gateway, providing centralized routing, authentication, request filtering, and communication between the frontend and backend microservices.

Other Services:

This project includes several microservices. For more details, please visit the repositories below:

Menu Service — Provides menu management with a GraphQL API

Order Service — Handles customer orders and order processing (REST API)

Notification Service — Sends real-time notifications via WebSocket

Eureka Server — Service discovery for microservices

Key Features:

Event-driven communication with Apache Kafka for real-time updates

Circuit Breaker (Resilience4j) for resilience and fault tolerance

Testing coverage with JUnit, Mockito, TestContainers, and GraphQL API tests

Layered architecture with SOLID principles for maintainability

AI-powered simple frontend for demonstration and testing purposes

Technologies Used:

Java 17, Spring Boot, Spring Cloud Gateway, Spring Security (JWT), PostgreSQL, GraphQL, WebSocket, Apache Kafka, Docker, Eureka, Resilience4j, JUnit, Mockito, TestContainers, Git

Contact:

Feel free to contact me for questions or contributions.
