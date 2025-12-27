# BPARK – Parking Management System

**Mid-Semester Academic Mini Project – ORT Braude College**

BPARK is a parking management system developed as a mid-semester academic mini project.  
The project focuses on **software architecture, client–server communication, and system design**, rather than full commercial-grade deployment or precise payment calculation.

The system is implemented using **Java**, **JavaFX**, an **OCSF-based client–server architecture**, and a **MySQL** database.

---

## 🚗 System Overview

BPARK simulates the core workflows of a parking management system, including reservations, parking session tracking, and management operations.

The main goals of the project are:
- Demonstrating a clean client–server architecture
- Practicing separation of concerns
- Implementing role-based system behavior
- Working with persistent data storage

---

## 👤 User Roles & Features

### Customer
- Register and log in as a subscriber
- Create parking reservations
- Enter parking lots using a generated parking code
- View current and future reservations
- View parking history

> **Note:** Payment calculation is intentionally simplified and is not the focus of this project.

---

### Parking Operations
- Track active parking sessions
- Handle parking entries and exits
- Manage parking extensions and late exits at a logical level
- Store parking history data

---

### Management
- Employee and manager login
- View system activity (active parkings and reservations)
- View subscriber details
- Perform basic management operations

---

### Terminal / Kiosk
- Parking code entry interface
- “Forgot code” flow
- Vehicle drop-off and pick-up screens
- Designed as a simulation of on-site parking terminals

---

## 🛠️ Architecture

The system follows a **client–server architecture**:

- **Client Side:** JavaFX desktop application  
- **Server Side:** OCSF-based server handling business logic and database access  
- **Shared Module:** Common entities and communication objects  
- **Database:** MySQL (local setup)

The project follows the **MVC (Model–View–Controller)** design pattern.

---

## 🧰 Technologies Used

- Java
- JavaFX
- OCSF (Object Client–Server Framework)
- MySQL
- JDBC
- MVC Design Pattern

---

## 📁 Project Structure

- `BparkClientSide/` – JavaFX client application  
- `BparkServerSide/` – OCSF server and database logic  
- `common/` – Shared entities and communication objects  
- `doc/` – Generated JavaDoc documentation  

---

## ▶️ Project Execution

This repository is intended for **code review and architectural demonstration**.

The system relies on a **local MySQL database** and environment-specific configuration, which are not included in the repository.  
As a result, the project is **not provided as a ready-to-run setup**.

The focus of this repository is to showcase:
- Client–server architecture
- System design and separation of concerns
- Java and JavaFX implementation
- Database interaction patterns

---
