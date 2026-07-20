# Phonebook Management System

A web-based Phonebook Management System developed as a Database Management Systems (DBMS) project. The application allows users to store, manage, search, update, and delete contact information through a user-friendly interface while maintaining data in a MySQL database.

---

## About the Project

The Phonebook Management System is designed to replace the traditional paper-based address book with a digital platform for efficient contact management. It enables users to organize personal and professional contacts in a structured database, making retrieval and maintenance faster and more convenient.

The project demonstrates fundamental DBMS concepts, including database design, CRUD operations, primary keys, searching, sorting, and structured data management.

---

## Objectives

- Digitally manage contact information.
- Provide quick and efficient search functionality.
- Organize contacts in a structured database.
- Demonstrate CRUD (Create, Read, Update, Delete) operations.
- Improve accessibility and organization of contact records.

---

## Features

- ➕ Add New Contacts
- 🔍 Search Contacts
- ✏️ Update Existing Contacts
- ❌ Delete Contacts
- 📋 View All Contacts
- 📂 Category-wise Contact Organization
- 🔠 Sort Contacts Alphabetically
- 📍 Sort Contacts by Location
- 🕒 View Recently Added Contacts

---

## Database Design

### Database Name
```
phonebook
```

### Table Name
```
Contacts
```

### Table Attributes

| Attribute | Description |
|-----------|-------------|
| ContactID | Unique identifier (Primary Key) |
| FirstName | First name of the contact |
| LastName | Last name of the contact |
| PhoneNumber | Phone number with country code support |
| Email | Email address |
| Address | Physical address including city and state |
| Category | Contact type (Family, Friend, Work, Emergency) |

---

## Primary Key

The **ContactID** uniquely identifies each contact stored in the database.

---

## Functionalities

### Add Contact
Insert new contact details into the database.

### Search Contact
Search contacts using:
- Name
- Phone Number
- Address
- Category

### Update Contact
Modify existing contact details.

### Delete Contact
Remove contacts from the database.

---

## Contact Views

The application provides multiple ways to view contacts:

- Complete Contact List
- Search Results
- Category-wise Contacts
- Individual Contact Details

---

## System Architecture

The application follows a Three-Tier Architecture.

```
        User Interface
              │
              ▼
Application / Database Layer
              │
              ▼
       MySQL Database
```

### Workflow

1. User enters contact information.
2. The application processes the request.
3. SQL queries are executed.
4. Data is stored or retrieved from the database.
5. Results are displayed on the interface.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- Visual Studio Code

---

## SQL Operations

The project performs the following database operations:

- INSERT
- SELECT
- UPDATE
- DELETE

These operations implement the complete CRUD functionality.

---

## Project Structure

```
Phonebook-Management-System/
│
├── index.html
├── style.css
├── script.js
├── add.php
├── update.php
├── delete.php
├── database.sql
└── README.md
```

*(Modify the project structure if your files are different.)*

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Phonebook-Management-System.git
```

### 2. Open the Project

Open the project folder in Visual Studio Code.

### 3. Start the Server

Start **Apache** and **MySQL** using XAMPP.

### 4. Create the Database

Create a database named:

```
phonebook
```

Import the provided SQL file into MySQL.

### 5. Run the Project

Open the following URL in your browser:

```
http://localhost/phonebook/
```

---

## DBMS Concepts Implemented

- Database Design
- Primary Key
- Tables
- CRUD Operations
- SQL Queries
- Searching
- Sorting
- Data Retrieval
- Structured Data Management

---

## Future Enhancements

- User Authentication
- Contact Images
- Favorite Contacts
- Import/Export Contacts
- Cloud Database Integration
- Mobile Responsive Design
- Backup & Restore
- Duplicate Contact Detection

---

## 👥 Team Members

- Vaani Pawan Khajuria
- Tanishh Suryavanshi

---

## 📄 License

This project was developed for educational purposes as part of the Database Management Systems (DBMS) course.
