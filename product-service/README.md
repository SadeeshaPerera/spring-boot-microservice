# Product Service Microservice

This project is a Spring Boot microservice for managing products, built for CTSE Module Lab 3. It demonstrates RESTful API development, in-memory database usage, and API documentation with Swagger.

## Features

- CRUD REST APIs for Product (id, name, price)
- In-memory H2 database for runtime persistence
- API documentation and testing via Swagger UI

## Technologies Used

- Spring Boot
- Spring Web
- H2 Database
- Springdoc OpenAPI UI

## Getting Started

### Prerequisites

- Java 17+
- Maven

### Build & Run

1. Build the project:
   ```bash
   mvn clean install
   ```
2. Run the application:
   ```bash
   mvn spring-boot:run -f product-service/pom.xml
   ```

### Access Swagger UI

- URL: [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

## API Endpoints

| Method | Endpoint         | Description           |
|--------|------------------|-----------------------|
| POST   | /products        | Create a product      |
| GET    | /products        | Get all products      |
| GET    | /products/{id}   | Get product by ID     |
| DELETE | /products/{id}   | Delete product by ID  |


