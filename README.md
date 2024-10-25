# 🏦 Bank Account Microservice

This project demonstrates the creation of a bank account management microservice using Spring Boot. The microservice allows CRUD operations on bank accounts and provides both RESTful and GraphQL APIs for interaction. Follow along to learn how to build and test each component!

## 📌 Project Requirements
1. **Spring Boot Project Setup** with dependencies:
   - 🌐 Web
   - 📊 Spring Data JPA
   - 🗃️ H2 Database
   - 🧩 Lombok

## ⚙️ Features and Steps

### 1. 📁 Project Setup
   - Create a new Spring Boot project with the dependencies listed above.

### 2. 🗄️ JPA Entity - `Compte`
   - Define the `Compte` entity to represent a bank account in the database.

### 3. 📂 Repository Layer
   - Create the `CompteRepository` interface based on Spring Data JPA to manage data access for `Compte` entities.

### 4. 🧪 DAO Layer Testing
   - Test the data access layer to ensure it performs CRUD operations correctly.

### 5. 🌐 RESTful Web Service
   - Implement a RESTful API to manage bank accounts (e.g., create, update, delete, and retrieve accounts).

### 6. 🔍 Testing the Microservice
   - Use Postman or another REST client to test each API endpoint for the bank account service.

### 7. 📜 Swagger Documentation
   - Generate and verify the Swagger documentation for the REST API endpoints.

### 8. 🚀 Expose API with Spring Data Rest and Projections
   - Simplify API exposure with Spring Data Rest and leverage projections to customize output data.

### 9. 📤 DTOs and Mappers
   - Create Data Transfer Objects (DTOs) and mappers to handle data transformation between layers.

### 10. 🛠️ Service Layer
   - Develop the business logic layer for handling the main microservice operations.

### 11. ⚡ GraphQL Web Service
   - Set up a GraphQL API for this microservice to allow flexible data querying using GraphQL.
   - Follow [this tutorial video](https://www.youtube.com/watch?v=FsdR09jlqaE) for additional guidance on integrating GraphQL.

## 🧰 Tools Used
- **Spring Boot** - Rapid application development framework.
- **H2 Database** - In-memory database for quick prototyping.
- **Lombok** - Reduces boilerplate code in Java.
- **Spring Data JPA** - Simplifies data access with JPA.
- **Swagger** - API documentation generator.
- **GraphQL** - Data query language for APIs.

## 🚀 Getting Started
To run the project locally:
1. Clone the repository.
2. Import it into your favorite IDE.
3. Build and run the application.

Use the Swagger UI at `/swagger-ui/index.html` to explore the REST APIs, or access the GraphQL endpoint for custom queries.

Happy coding! ✨
