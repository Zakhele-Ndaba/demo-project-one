# Demo Project One

A simple Spring Boot demo project with MySQL database connectivity.

## Overview

This project is a basic Spring Boot application that demonstrates:
- REST API development
- MySQL database integration
- JPA/Hibernate ORM usage
- User entity CRUD operations

## Technologies

- Java 17
- Spring Boot 3.2.2
- Spring Data JPA
- MySQL
- Maven
- Lombok

## Prerequisites

- JDK 17 or higher
- Maven
- MySQL Server

## Setup

1. Clone the repository
2. Configure the database connection in `src/main/resources/application.properties`
3. Run the application using Maven: `mvn spring-boot:run`

## Database Configuration

The default database configuration is:
- URL: `jdbc:mysql://localhost:3306/demo_db`
- Username: `root`
- Password: `password`

You should modify these settings according to your environment.

## Project Structure

- `model`: Contains entity classes
- `repository`: Contains Spring Data JPA repositories
- `service`: Contains business logic
- `controller`: Contains REST endpoints
- `config`: Contains configuration classes

## License

This project is open source and available under the [MIT License](LICENSE).