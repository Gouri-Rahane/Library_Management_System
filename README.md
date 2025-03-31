
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Overview

The Library Management System is a desktop application developed using Java Swing and MySQL. It is designed to help libraries manage books, users, and transactions efficiently.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Features

User Authentication: Admin and librarian login.

Book Management: Add, update, delete, and search books.

Member Management: Register, update, and remove members.

Issue & Return Books: Track book lending and returns.

Database Connectivity: Stores data in a MySQL database.

User-friendly Interface: Built with Java Swing for a simple and interactive UI.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Technologies Used

Java (Swing, AWT)

MySQL

JDBC (Java Database Connectivity)

NetBeans/Eclipse (Optional for development)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Installation

Prerequisites

Install Java JDK (version 8 or later)

Install MySQL Server and MySQL Workbench

Install NetBeans/Eclipse (Optional for IDE support)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Setup Steps

Clone the repository:

git clone https://github.com/your-username/library-management-system.git
cd library-management-system

Import the project into your preferred Java IDE.

Configure the database:

Create a MySQL database:

CREATE DATABASE library_db;

Import the provided SQL file (library_db.sql) into MySQL.

Update the database connection details in the DBConnection.java file.

Compile and run the project.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Usage

Admin/Librarian Login: Use default credentials or create new ones.

Manage Books: Add, update, and delete books from the system.

Manage Members: Register new members and update details.

Issue & Return Books: Track lending and return dates.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
