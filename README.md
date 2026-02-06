# Task Management System

A simple Task Management System built with React.js and Spring Boot. Users can login and perform CRUD operations on their tasks.

## 📋 Overview

This is a full-stack web application where users can login and manage their tasks with basic Create, Read, Update, and Delete operations.

## ✨ Features

- User Login
- Create tasks
- View all tasks
- Update tasks
- Delete tasks

## 🛠 Tech Stack

**Frontend**
- React.js
- HTML
- CSS
- JavaScript

**Backend**
- Spring Boot
- Java
- REST API

**Database**
- MySQL

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- Java JDK 8+
- MySQL
- Maven

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/task-management-system.git
cd task-management-system
```

2. **Setup MySQL Database**
```sql
CREATE DATABASE task_management_system_db;
```

3. **Configure Backend**
   
   Update `application.properties` in `backend/src/main/resources/`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/task_management_system_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

4. **Run Backend**
```bash
cd backend
mvn spring-boot:run
```
Backend runs on: `http://localhost:8080`

5. **Run Frontend**
```bash
cd frontend
npm install
npm start
```
Frontend runs on: `http://localhost:3000`


6. **Snapshots**
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34864c2d-b9f4-4fa6-a328-4d8a3dea03f9" />

   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c7571ad6-9ceb-46a1-a056-960435f5bf4b" />


