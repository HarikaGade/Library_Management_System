# 📚 Library Management System

A complete Java-based Library Management System built using NetBeans and MySQL. This project provides a simple yet functional interface to manage library operations such as book inventory and staff records with secure login access.

---

## 🖥️ Tech Stack

### Front-End:
- **Language:** Java (Swing for GUI)
- **IDE:** NetBeans

### Back-End:
- **Database:** MySQL

---

## ✅ Functional Modules

### 🔐 Login Page
- Secure login for admin (via MySQL `Admin` table)

### 📘 Book Management
- **Books Available:** View all available books
- **Add Books:** Insert new books into the database
- **Remove Books:** Delete books from the library

### 👨‍🏫 Staff Management
- **Staff Details:** View existing staff info
- **Add Staff:** Insert new staff entries
- **Remove Staff:** Remove staff records

---

## 🗄️ Database Design (MySQL Tables)

1. **Admin Table**
   - Stores admin login credentials

2. **Books Table**
   - Stores details like Book ID, Title, Author, Category, Availability

3. **Staff Table**
   - Contains Staff ID, Name, Position, Contact Info

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 8+
- NetBeans IDE
- MySQL Server and Workbench

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Library_Management_System.git
```
### 2. Set Up the Database

- Open MySQL Workbench
- Create a new database (e.g., `library_db`)
- Import the `library.sql` file (if provided) OR manually create:
  - `admin` table
  - `books` table
  - `staff` table

### 3. Configure Database Connection

- In NetBeans, open your project.
- Go to the class where your MySQL connection is defined.
- Update the credentials as needed:
```java
String url = "jdbc:mysql://localhost:3306/library_db";
String user = "root";
String password = "your_password";
```
4. Run the Project
Build and run the project via NetBeans

Login using admin credentials

Access all features through the GUI

📂 Project Structure
```bash
Library_Management_System/
├── nbproject/         # NetBeans project configuration
├── src/               # Source code and GUI forms
│   ├── Login.java
│   ├── Add_Books.java
│   ├── Remove_Books.java
│   ├── Add_Staff.java
│   ├── Remove_Staff.java
│   ├── Staff_Details.java
│   └── ...
├── manifest.mf
├── build.xml
└── README.md
```

![Screenshot 2025-07-02 094139](https://github.com/user-attachments/assets/6f0483ec-1113-4b8b-880e-87a2133016e0)

![Screenshot 2025-07-02 094202](https://github.com/user-attachments/assets/f2068d34-42d0-461d-9ae9-22966960e0e8)

![image](https://github.com/user-attachments/assets/b979fd5a-1155-463a-b33e-954f9de80ad7)




