# 📚 Library Management System (Java Spring Boot)

A Java-based Library Management System built and customized by **Debjit Das**.  
This project automates book cataloging, user registration, borrowing/returning, and overdue tracking — helping libraries reduce manual work and improve efficiency.

---

## 📖 Table of Contents
- [General Info](#general-info)
- [Features](#features)
- [Technologies](#technologies)
- [Database Model](#database-model)
- [Getting Started](#getting-started)
- [Author](#author)

---

## 📝 General Info
The **Library Management System** is a full-stack web application that manages library operations such as adding books, registering users, borrowing/returning resources, and sending notifications.  

This version has been extended and documented by **Debjit Das** to demonstrate skills in **Java, OOP, Spring Boot, PostgreSQL, and full-stack development**.

---

## 🚀 Features

### 🔑 User Management
- Role-based access (Admin / Librarian / Member)
- Add, edit, and delete users
- Authentication (login/logout with Spring Security)
- View user profiles with search, filtering, and pagination

### 📚 Library Resources
- Manage Authors, Categories, Books, and Works
- Add, edit, update, and delete records
- Search, filter, and paginate resources

### 🔄 Borrowing / Loan Management
- Issue and return library books
- Limit members to max `5` borrowed books at once
- Track current and past loans
- Fine calculation for overdue books *(new feature suggestion)*

### 📧 Mail Notifications
- Welcome email on account creation
- Loan start / return notifications

---

## 🛠 Technologies Used
- **Java** (OOP, Collections, JDBC)
- **Spring Boot** (Spring MVC, Spring Security, Hibernate)
- **Thymeleaf** for server-side rendering
- **Bootstrap, HTML, CSS, JavaScript** for UI
- **PostgreSQL / MySQL** for database
- **Docker** for deployment
- **Maven** as build tool
- **IntelliJ IDEA / VS Code**

---

## 🗄 Database Model
![Database Diagram](https://user-images.githubusercontent.com/92815435/218085760-eda35b13-4193-4f88-a39c-9d8345a842e0.png)

---

## ▶️ Getting Started

### Prerequisites
- Install **Java 17+**
- Install **Maven**
- Install **Docker** (for containerized deployment)

### Run the Application

1. Clone this repo:
   ```bash
   git clone https://github.com/debjit699971/Library-Management-System-Debjit.git
   cd Library-Management-System-Debjit