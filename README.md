# Fitness Microservices

A fitness application built using a microservices architecture, with a React frontend and Java Spring Boot backend services.

## Overview

Fitness Microservices is a project designed to manage fitness-related activities using multiple backend services. The project separates responsibilities into individual services to improve modularity and maintainability.

## Tech Stack

- **Backend:** Java, Spring Boot
- **Frontend:** React, JavaScript, Vite
- **Service Discovery:** Netflix Eureka
- **API Gateway:** Spring Cloud Gateway
- **Configuration:** Spring Cloud Config
- **Database:** PostgreSQL
- **Build Tool:** Maven

## Project Structure

```text
fitness-microservices/
├── activityservice/
├── aiservice/
├── configserver/
├── eureka/
├── gateway/
├── userservice/
└── fitness-frontend/
```

## Architecture

The application consists of separate services:

- **User Service:** Handles user-related operations.
- **Activity Service:** Handles fitness activity-related operations.
- **AI Service:** Provides AI-related functionality.
- **Eureka Server:** Supports service discovery.
- **Config Server:** Centralizes application configuration.
- **API Gateway:** Provides an entry point for frontend API requests.
- **React Frontend:** Provides the user interface.

## Prerequisites

Install the following before running the project:

- Java JDK
- Maven
- Node.js and npm
- PostgreSQL

## Getting Started

1. Clone this repository.
2. Configure the database connection and application settings.
3. Start the Config Server.
4. Start the Eureka Server.
5. Start the backend microservices.
6. Start the API Gateway.
7. Start the React frontend.

Detailed commands and configuration instructions can be added after verifying the requirements of each service.

## Future Improvements

- Add automated tests.
- Improve error handling and logging.
- Add deployment configuration.
- Add API documentation.
- Improve monitoring and observability.

## Author

Gagandeep

GitHub: [gagan-288](https://github.com/gagan-288)
