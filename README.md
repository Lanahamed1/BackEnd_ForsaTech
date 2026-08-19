# 🗂️ Forsa-Tech REST API
A RESTful backend API built with Django and Django REST Framework to power the FORSA-TECH HR and recruitment platform.

The API provides authentication, authorization, candidate management, CV management, employer management, job management, applications, and recruitment workflows.

---

## 🚀 Overview

The FORSA-TECH REST API serves as the backend layer for the FORSA-TECH recruitment platform.

It provides structured RESTful endpoints that allow the Flutter Web frontend to communicate with the backend and manage recruitment-related data.

The API follows a client-server architecture and separates business logic, authentication, database operations, and frontend presentation.

---

## ✨ Features

### 🔐 Authentication

- JWT authentication
- User registration
- User login
- Token-based authorization
- Protected API endpoints

### 👤 User Management

- User profiles
- Candidate management
- Employer management
- Role-based access control

### 📄 CV Management

- CV creation
- CV management
- Candidate professional information

### 💼 Job Management

- Create jobs
- Update jobs
- Delete jobs
- Retrieve available jobs
- Job application management

### 📋 Recruitment

- Candidate applications
- Application management
- Recruitment workflows
- Employer-side candidate management

---

## 🏗️ Architecture

```text
Flutter Web Frontend
        │
        │ HTTP / REST
        ▼
Django REST Framework
        │
        ▼
   Business Logic
        │
        ▼
     Database


| Technology            | Purpose              |
| --------------------- | -------------------- |
| Python                | Backend Language     |
| Django                | Web Framework        |
| Django REST Framework | API Development      |
| JWT                   | Authentication       |
| SQLite                | Database             |
| REST API              | Client Communication |

📌 Project Status

Backend API developed as part of the FORSA-TECH full-stack HR and recruitment platform.

🔗 Frontend

The API is consumed by the FORSA-TECH Flutter Web application.

Frontend repository:

https://github.com/Lanahamed1/Forsa-Tech-HR


```bash
git clone https://github.com/lanahamed1/BackEnd_ForsaTech



👨‍💻 Author

Lanahamed

GitHub:

https://github.com/Lanahamed1
