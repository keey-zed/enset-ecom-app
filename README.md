# Microservices Architecture with Spring Cloud: Use Case

This project showcases a microservices architecture built using Spring Cloud. The use case involves creating an application based on two core business services: Vault, Customer Service, and Inventory Service, all orchestrated using various Spring Cloud technical services.

## Table of Contents

- [Overview](#overview)
- [Services](#services)
- [Service Orchestration](#service-orchestration)
- [Frontend Application](#frontend-application)

## Overview

The microservices architecture in this project is designed to illustrate the use of Spring Cloud for building distributed systems. It consists of the following key components:

- **Vault Service**: A service responsible for managing secrets and sensitive configuration information.

- **Customer Service**: A service for managing customer-related data and functionality.

- **Inventory Service**: A service responsible for managing inventory and related operations.

- **Consul Registry**: A service registry and discovery mechanism that enables service registration and discovery.

- **Spring Cloud Gateway Service**: Acts as a service proxy and provides routing and load balancing for microservices.

- **Order Service**: A service for managing orders.

- **Spring Cloud Config Service**: Provides centralized configuration management for services.

- **Angular Frontend**: A web frontend for interacting with the microservices.

## Services

The microservices in this project are as follows:

### Vault Service

- Responsibilities: Manages secrets and sensitive configuration information.
- Use: Sharing secrets securely between services.

### Customer Service

- Responsibilities: Manages customer-related data and functionality.
- Use: Managing customer data and interactions.

### Inventory Service

- Responsibilities: Manages inventory and related operations.
- Use: Tracking and managing product inventory.

### Order Service

- Responsibilities: Manages orders.
- Use: Handling customer orders and order-related operations.

### Spring Cloud Gateway Service

- Responsibilities: Acts as a service proxy, routing and load balancing for microservices.
- Use: Routing and load balancing requests to the appropriate microservices.

### Spring Cloud Config Service

- Responsibilities: Provides centralized configuration management for services.
- Use: Managing configuration settings for all services.

## Service Orchestration

Service orchestration is achieved using Spring Cloud technologies:

- **Consul Registry**: This is used for service registration and discovery. Services register with the Consul registry, making it easier for other services to discover and communicate with them.

- **Spring Cloud Gateway Service**: Acts as a service proxy, routing and load balancing requests to the appropriate microservices.

- **Spring Cloud Config**: Centralized configuration management for services.

## Frontend Application

The project includes a web frontend built using Angular. This frontend allows users to interact with the microservices and access various functionalities offered by the services.
