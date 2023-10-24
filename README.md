# Microservices Architecture with Spring Cloud: Use Case

This project demonstrates a microservices architecture using Spring Cloud for a specific use case. The architecture is based on three core business services:

1. **Customer Management Service**
2. **Inventory Management Service**
3. **Order Management Service**

These services interact to provide a complete solution for managing customers, inventory, and orders.

## Architecture Overview

The orchestration of services is achieved through various Spring Cloud technical services and tools, ensuring robust, scalable, and reliable microservices communication and operation:

- **Spring Cloud Gateway Service**: This service acts as a proxy, routing requests to the appropriate microservices.

- **Consul Registry Service**: Consul is used as a service registry, providing a centralized location for service discovery and registration.

- **Consul Config and Spring Cloud Config**: These services enable externalized configuration management for microservices, making it easier to manage application configurations in a distributed environment.

- **Vault Config (Secret Sharing)**: Vault is used to securely store and share secrets and sensitive information between services.

- **Resilience4J Circuit Breaker**: To enhance the fault tolerance and resilience of microservices, Resilience4J is employed as a circuit breaker framework.

- **Web Frontend (Angular)**: The web frontend is built using Angular, providing an intuitive user interface for interacting with the microservices.

## Services

### Customer Management Service

The Customer Management Service is responsible for managing customer information, including creating, updating, and retrieving customer data.

### Inventory Management Service

The Inventory Management Service handles inventory-related tasks, such as managing product availability, quantities, and updates.

### Order Management Service

The Order Management Service takes care of processing and managing customer orders, including order creation, status updates, and order history.

## Getting Started

To get started with this project, follow these steps:

1. **Setup and Configuration**: Configure and set up the necessary Spring Cloud components, including Consul Registry, Consul Config, and Vault Config.

2. **Build and Deploy Microservices**: Build and deploy the Customer Management Service, Inventory Management Service, and Order Management Service.

3. **Configure Spring Cloud Gateway**: Configure Spring Cloud Gateway to act as a proxy, routing requests to the appropriate microservices.

4. **Build and Deploy Angular Frontend**: Build and deploy the Angular web frontend for user interaction.

5. **Testing and Usage**: Test and use the microservices and web frontend to manage customers, inventory, and orders.
