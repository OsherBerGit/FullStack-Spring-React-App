# 🍃 Spring Boot & React Full-Stack Engine

![Java 21](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Security](https://img.shields.io/badge/Security-JWT-red?style=for-the-badge)

<!--
<div align="center">
  <img src="https://via.placeholder.com/800x400.png?text=Full+Stack+Architecture+Preview" alt="App Preview" width="90%"/>
</div>
-->

## 📖 About
**Full-Stack Spring & React App** is a robust, production-ready architectural template designed for building scalable enterprise web applications.

It bridges the gap between a powerful **Java 21 / Spring Boot 3** backend and a dynamic **React (Vite)** frontend. The project serves as a reference implementation for RESTful API communication, secure authentication flows, and efficient data persistence.

## 🛠 Tech Stack

### Backend (Server)
* **Core:** Java 21, Spring Boot 3
* **Security:** Spring Security, JWT (JSON Web Tokens)
* **Data:** Spring Data JPA, Hibernate, MySQL 8.0
* **Documentation:** SpringDoc OpenAPI (Swagger UI)

### Frontend (Client)
* **Framework:** React.js (SPA)
* **Build Tool:** Vite (Hot Module Replacement)
* **Styling:** CSS3 / Styled Components
* **HTTP Client:** Axios / Fetch API

## ✨ Highlights & Features

### 🔐 Enterprise Security
* **Stateless Authentication:** Fully implemented **JWT** (JSON Web Token) authentication flow.
* **Protected Routes:** Spring Security configuration ensuring only authenticated users can access sensitive endpoints.

### 🏗️ Robust Architecture
* **RESTful API:** Clean separation of concerns with standard HTTP methods.
* **Reactive UI:** Single Page Application (SPA) providing a seamless user experience without page reloads.
* **Auto-Documentation:** Integrated **Swagger UI** for testing and visualizing backend endpoints in real-time.

### 💾 Data Management
* **ORM Layer:** Uses **Hibernate** for efficient object-relational mapping.
* **Database:** Optimized for **MySQL 8.0** with connection pooling.

## 🚀 Quick Start
To run the full stack environment locally:

### 1. Database Setup
Ensure you have MySQL running and create a schema:
```sql
CREATE DATABASE fullstack_db;
```

### 2. Backend (Spring Boot)
```cd backend
./mvnw spring-boot:run
```

The server will start on port 8080.

### 3. Frontend (React)
```cd frontend
npm install
npm run dev
```

The client will run on http://localhost:5173.

This repository demonstrates the ability to architect a complete end-to-end solution, handling the complexities of connecting a strongly-typed backend with a modern JavaScript frontend.
