# 🩸 Desktop Blood Donation Management System **Java Swing + MySQL**

A desktop-based Blood Donation Management System developed using **Java Swing** for the graphical user interface and **MySQL** for database management.  
The application allows users to register, log in, request blood, register as donors, and view their history, while providing a dedicated **Admin Panel** to manage all system records.

## 🎯 Project Objective

The main goal of this project is to create a **simple, user-friendly desktop application** that:
- Manages blood donation records efficiently
- Connects blood donors with blood requests
- Allows administrators to monitor and control the entire system

This project is developed for **academic learning purposes** 🚀

## 🚀 Technologies Used

- **Java** (Core Language)
- **Java Swing** (Graphical User Interface)
- **JDBC** (MySQL Database Connectivity)
- **MySQL** (Database Storage)
- **XAMPP** (Local MySQL Server)


## ✨ Project Features

### 👤 User Features
- User Registration  
  - Full Name  
  - Username & Password  
  - Location (Province, City, Postal Code)
- User Login (Plain text passwords – academic use only)
- Request Blood  
  - Select Blood Type  
  - Select Location
- Register as Donor  
  - Blood Type  
  - Availability  
  - Contact Number  
  - Email Address
- View Personal Request History
- Light / Dark Theme Toggle
- Secure Logout
  

### 🛠️ Admin Features
- Hardcoded Admin Login  
  - **Username:** `admin`  
  - **Password:** `admin123`
- View All Registered Users
- View All Blood Requests
- View All Registered Donors


## 🎨 User Interface

- Modern **red-themed design**
- Gradient backgrounds
- Custom styled buttons
- Clean and user-friendly layouts
- 

## 🗄️ Database Design

The application uses **MySQL** with separate tables for:
- Users
- Locations
- Donors
- Blood Requests


## 🛠️ How to Run the Project

1. Install **XAMPP** (or any MySQL server).
2. Start **MySQL** from the XAMPP Control Panel.
3. Open **phpMyAdmin** and create a new database: **blood_donation_db**
4. Extract the rar file downloaded from repository
5. Import the **blood_donation_db(1)** into database
6. Open the project in **NetBeans** or any Java IDE.
8. Download and add **MySQL Connector/J** to the project libraries: (https://dev.mysql.com/downloads/connector/j/)
9. Add the JAR file (e.g., `mysql-connector-j-8.x.x.jar`) to the project classpath.
10. Update `DBConnection.java` if required:
   * Database URL
   * Username (default: `root`)
   * Password (default: blank)

11. Run:
   * `Main.java` **OR**
   * `BloodDonationSystem1.java`

11. The login screen will appear 🎉
    * Register a new user **OR**
    * Login as admin (`admin / admin123`)


## 📌 Notes

* This project is intended for **educational purposes**.
* Passwords are stored in **plain text** and are **not recommended for production use**.
* Future improvements may include password hashing, role-based access, and online deployment.


## 👨‍💻 Author

**Saad Ahmed**
Developed as a **Desktop Application Project** using Java Swing & MySQL.

