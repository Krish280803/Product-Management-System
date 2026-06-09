# Product Management System

 Overview
Product Management System is a Spring Boot REST API application that performs CRUD operations on products using Spring Data JPA and MySQL Database.

 Technologies Used
- Java 17
- Spring Boot 3
- Spring Data JPA
- MySQL
- Maven
- Postman

 Project Structure

com.product
├── controller
├── entity
├── repository
├── service
└── ProductManagementApplication

 Database Configuration

Database Name:
product_db

application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/product_db
spring.datasource.username=root
spring.datasource.password=Root@12345

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

 API Endpoints

 Get All Products
GET /products

 Get Product By ID
GET /products/{id}

 Add Product
POST /products

Request Body

{
    "name":"Laptop",
    "price":50000,
    "quantity":10
}

 Update Product
PUT /products/{id}

 Delete Product
DELETE /products/{id}

 Testing

All REST APIs are tested using Postman.

 Author

Srikrishna
