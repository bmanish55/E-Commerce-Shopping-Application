# E-Commerce-Shopping-Application

A full-featured e-commerce platform built with:
- **Spring Boot 3.2.3** (Java 17)
- **MySQL 8.0+** (Database)
- **Thymeleaf** (Frontend)
- **Spring Security** (Authentication)
- 
<img width="1895" height="886" alt="Screenshot 2025-08-15 225818" src="https://github.com/user-attachments/assets/f68fff75-5a5b-4065-874d-637337380646" />


<img width="1849" height="884" alt="Screenshot 2025-08-15 225724" src="https://github.com/user-attachments/assets/34cce86e-27c3-4334-aa70-16d4c1ce093d" />


## 🚀 Quick Start

### Prerequisites
- Java 17 ([Download](https://adoptium.net/))
- MySQL 8.0+ ([Download](https://dev.mysql.com/downloads/))
- Maven 3.6+

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ecommerce-spring-boot.git
## Database Setup:
CREATE DATABASE ecommerce_db;
CREATE USER 'ecom_user'@'localhost' IDENTIFIED BY 'SecurePass123!';
GRANT ALL PRIVILEGES ON ecommerce_db.* TO 'ecom_user'@'localhost';
FLUSH PRIVILEGES;

## Configure application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db?createDatabaseIfNotExist=true
spring.datasource.username=ecom_user
spring.datasource.password=SecurePass123!
spring.jpa.hibernate.ddl-auto=update

## 🛠️ Admin Access
Default admin credentials (or register at /admin/add-admin):
Email: admin@example.com
Password: admin123

## 🌟 Key Features
-User/Admin authentication
-Product & Category management
-Shopping cart
-Order processing
-Responsive UI

## 💻 Java 17 Requirements
Ensure JAVA_HOME points to JDK 17

Verify version:
java -version
# Should show: openjdk 17.x.x
