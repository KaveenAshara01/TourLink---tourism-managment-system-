# 🌍 TourLink - Tourism Management System

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.2-green?style=for-the-badge&logo=spring-boot)
![Angular](https://img.shields.io/badge/Angular-Frontend-red?style=for-the-badge&logo=angular)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![Security](https://img.shields.io/badge/Spring_Security-Protected-green?style=for-the-badge&logo=spring-security)

## 📖 Overview

**TourLink** is a modern, comprehensive web application designed to revolutionize tourism management. The platform features an innovative **freelance work model** that empowers Tour Guides and Drivers to connect directly with travelers and agencies. 

Built with a robust **Spring Boot** backend and a dynamic **Angular** frontend, TourLink ensures a seamless, secure, and scalable experience for all users. The system leverages **MySQL** for reliable data persistence and implements advanced security protocols to protect user data and transactions.

---

## 🚀 Key Features

### 🛡️ Core Functionality
- **Freelance Ecosystem**: Dedicated portals for Tour Guides and Drivers to register, manage their profiles, and accept freelance opportunities.
- **Tour Management**: Comprehensive tools for creating, booking, and managing tour packages.
- **Tourist Management**: User-friendly interface for tourists to browse, book, and review services.

### 🔐 Security & Architecture
- **Advanced Authentication**: Implemented using Spring Security with robust protocols (JWT/OAuth2 readiness).
- **Role-Based Access Control (RBAC)**: secure endpoints ensuring that Admins, Guides, Drivers, and Tourists only access authorized resources.
- **RESTful API Design**: Scalable and well-documented APIs powering the connection between the Angular frontend and Java backend.

---

## 🛠️ Technology Stack

| Component | Technology | Version | Description |
|-----------|------------|---------|-------------|
| **Backend** | Java | 17 LTS | Core language |
| | Spring Boot | 3.2.2 | Application framework |
| | Spring Data JPA | - | ORM / Database interaction |
| | Spring Security | - | Authentication & Authorization |
| **Frontend** | Angular | Latest | SPA Client Framework |
| **Database** | MySQL | 8.0+ | Relational Database |
| **Build Tool** | Maven | - | Dependency Management |

---

## ⚙️ Getting Started

Follow these instructions to set up the project on your local machine.

### Prerequisites
- **Java Development Kit (JDK) 17** or higher
- **Node.js & npm** (for Angular)
- **MySQL Server**
- **Maven**
- **Git**

### 1. Clone the Repository
```bash
git clone https://github.com/Kaveenashara01/TourLink.git
cd TourLink
```

### 2. Database Setup
1. Open your MySQL client (Workbench/CLI).
2. Create the database:
   ```sql
   CREATE DATABASE `Travel-agency-management-system`;
   ```
3. Update database credentials in `src/main/resources/application.properties` if necessary:
   ```properties
   spring.datasource.username=root
   spring.datasource.password=12345
   ```

### 3. Backend Setup
Navigate to the backend directory and run the application:
```bash
cd Travel-agency-management-system
mvn spring-boot:run
```
*The backend server will start at `http://localhost:8082`*

### 4. Frontend Setup (Angular)
*Navigate to the frontend directory (if located within repository) or ensure the independent frontend project is linked.*
```bash
# Example commands
npm install
ng serve
```
*The frontend application typically is accessible at `http://localhost:4200`*

---

## 📂 Project Structure

```
TourLink/
├── Travel-agency-management-system/   # Spring Boot Backend
│   ├── src/main/java/                 # Java Source Code
│   │   └── com/example/travel.../     # Controllers, Services, Repositories, Entities
│   ├── src/main/resources/            # Configuration & Static Resources
│   └── pom.xml                        # Maven Dependencies
└── [Frontend Directory]               # Angular Application Source
```

---


