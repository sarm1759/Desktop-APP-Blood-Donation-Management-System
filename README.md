🩸 Desktop Blood Donation Management System (Java Swing + MySQL)

This project is a desktop-based Blood Donation Management System developed using Java Swing for the GUI and MySQL for the database. It allows users to register, log in, request blood, register as donors, and view history, while providing a separate admin panel to manage and view all records.

🩸 Project Objective

The main goal is to create a simple, user-friendly desktop application that helps manage blood donation records, connect donors with requests, and allow administrators to oversee the system efficiently.
🚀 Technologies Used

Java (Core language)
Java Swing (For graphical user interface)
JDBC (For MySQL database connectivity)
MySQL (Database storage)
XAMPP (Local server for MySQL – recommended for running the database)

📂 Project Features

User Registration → with full name, username, password, and location (province, city, postal code)
User Login → secure login (plain text passwords – note: for academic use)
Hardcoded Admin Login → (username: admin, password: admin123)
User Dashboard →
Request Blood (select blood type and location)
Register as Donor (blood type, availability, contact, email)
View Personal Request History
Toggle Theme (Light/Dark mode)
Logout

Admin Dashboard →
View All Users
View All Blood Requests
View All Registered Donors

Beautiful UI → Gradient backgrounds, custom styled buttons, modern red-themed design
Database Integration → Separate tables for users, locations, donors, and blood requests

🛠️ How to Run the Project

Install XAMPP (or any MySQL server) on your PC.
Start MySQL from XAMPP Control Panel.
Open phpMyAdmin and create a new database named blood_donation_db.
Create the required tables (SQL schema below) or import if you have a dump file.
Open the project in NetBeans or any Java IDE.
Add MySQL Connector/J JAR file to your project libraries:
Download from: https://dev.mysql.com/downloads/connector/j/
Add the JAR (e.g., mysql-connector-j-8.x.x.jar) to your project's classpath.

Update DBConnection.java if needed (URL, username, password – default is root with blank password).
Run Main.java or BloodDonationSystem1.java (both start the Login form).
Boom! The application will launch. Register a user or login as admin / admin123.
