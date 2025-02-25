# Simple Task Manager

A lightweight task management web application built using Spring Boot, JPA, and PostgreSQL (or H2 for in-memory testing). This project provides RESTful endpoints for user registration and ticket management (creating, updating, deleting, and retrieving tickets). Developed with Postman for API testing and Frontend replication. Power BI to demonstrate data visualisation.

## Features

- **User Registration:**  
  Users can sign up with a username, password, role (e.g., STUDENT, ADMIN, STAFF), and an optional status.
  
- **Ticket Management:**  
  Users (students) can create enquiries/tickets which are assigned to an admin or staff member.  
  Admin/Staff can update any ticket (including reporter and assignee changes) while students are limited to updating their own ticket details.

- **Automated Data Seeding:**  
  Optionally seed the database with test data via an SQL script or programmatic seeding using an `ApplicationRunner`.

- **API Testing:**  
  Use Postman to easily test all endpoints.

- **Data Visualization:**  
  Export or connect the application's database to Power BI to create interactive dashboards.

## Technologies Used

- **Spring Boot** – Rapid application development and dependency management.
- **Spring Data JPA** – ORM support and database persistence.
- **Jakarta Bean Validation** – For input validations using annotations like `@NotBlank` and `@NotNull`.
- **Lombok** – To reduce boilerplate code (optional).
- **PostgreSQL / PgAdmin** – Database support (PostgreSQL for production; H2 for in-memory testing).
- **Postman** – For API testing.
- **Power BI** – For creating visual dashboards from your data.

## Getting Started

### Prerequisites

- Java 17 or later
- Maven 3.x
- PostgreSQL (if using PostgreSQL) or H2 in-memory (default configuration)
- Postman for API testing
- Power BI Desktop (optional, for visualisation)

