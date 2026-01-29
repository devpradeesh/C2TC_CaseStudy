# C2TC Case Study – Food Delivery Application (Spring Boot)

This project is developed as part of the C2TC Case Study using **Java Spring Boot**.  
It represents a basic **Food Delivery Management System** with backend APIs.

---

## 🚀 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- MySQL Database
- Maven
- REST API

---

## 📁 Project Structure


---

## 🎯 Features

- Add Food Items
- View Food Items
- Update Food Details
- Delete Food Items
- Customer Order Management
- Database Integration using JPA

---

## 🗄️ Database Configuration

Update your `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fooddelivery
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
## 📦 Dependencies Used

- spring-boot-starter-web
- spring-boot-starter-data-jpa
- spring-boot-starter-validation
- mysql-connector-j
- lombok
- spring-boot-devtools


## 🧩 System Design (Concept)

The application follows layered architecture:

Controller → Service → Repository → Database

Entities involved:
- Food
- Customer
- Order


## 🛠️ Tools Used

- Eclipse / IntelliJ IDEA
- Postman (API Testing)
- MySQL Workbench
- Git & GitHub


## 🔍 API Testing using Postman

All APIs are tested using Postman.

Example:

POST /food  
Body:
{
  "name": "Pizza",
  "price": 250
}


## 🧠 Concepts Covered

- REST Controller
- Dependency Injection
- JPA Repository
- Hibernate ORM
- Exception Handling
- MVC Architecture


## 🚧 Future Enhancements

- User Authentication (Spring Security)
- Swagger API Documentation
- Frontend Integration (React / Angular)
- Docker Deployment


## 📜 License

This project is developed for educational purposes as part of C2TC training.
