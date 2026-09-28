# NutriOrder-AI
## Smart Food & Health Platform

[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://openjdk.java.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)](https://www.mysql.com/)

A backend-focused platform combining **food ordering** with **nutrition tracking** and personalized health insights using Java, Spring Boot, and Spring Security.

---

## 🚀 Features

### Implemented ✅
- User registration and authentication
- JWT-based security with BCrypt password hashing
- Restaurant and food item management
- Order placement and tracking
- Nutrition tracking (calories, protein, carbs, fat)
- RESTful APIs with proper HTTP status codes
- Input validation and exception handling

### In Progress 🚧
- Daily nutrition summaries
- Personalized food recommendations
- Advanced search and filtering
- Admin dashboard APIs

### Planned 📋
- Microservices architecture
- Event-driven communication with Apache Kafka
- AI-assisted nutrition insights
- Mobile app integration

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Language** | Java 17 |
| **Framework** | Spring Boot 3.x, Spring Security |
| **Database** | MySQL 8.0 |
| **Security** | JWT, BCrypt |
| **API Testing** | Postman |
| **Build Tool** | Maven |
| **Version Control** | Git & GitHub |

---

## 🏗️ Architecture

The backend follows a clean **Controller → Service → Repository** layered architecture:

### Security Flow
1. User registers → Password hashed with BCrypt
2. User logs in → JWT token generated
3. Subsequent requests → JWT validated in Authorization header
4. Protected endpoints → User-specific data isolation

---
## 📦 Project Structure

---

## 🚀 How to Run

### Prerequisites
- Java 17+
- MySQL 8.0
- Maven 3.6+

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/NutriOrder-AI.git
   cd NutriOrder-AI
   ```

2. **Configure MySQL**
   ```bash
   mysql -u root -p
   CREATE DATABASE nutriorder_db;
   ```

3. **Update application.properties**
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/nutriorder_db
   spring.datasource.username=root
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   ```

4. **Run the application**
   ```bash
   mvn spring-boot:run
   ```

5. **Access APIs**
    - Base URL: `http://localhost:8080`

---

## 📝 Project Status

**Status:** Actively in Development

| Phase | Status |
|-------|--------|
| Project Setup | ✅ Complete |
| Authentication & JWT | 🚧 In Progress |
| Core Food Ordering | 🚧 In Progress |
| Nutrition Tracking | 📋 Planned |
| Testing & Documentation | 🚧 In Progress |

---

## 📬 Contact

**Developer:** Divyanshi Rathore  
**Location:** Noida, Uttar Pradesh, India  
**GitHub:** [@yourusername](https://github.com/yourusername)

---

## 📄 License

This project is open source and available under the MIT License.


