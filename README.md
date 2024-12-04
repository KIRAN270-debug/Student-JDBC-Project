Student JDBC Project
This is a Java-based console application that manages student information using JDBC (Java Database Connectivity). The project allows the user to perform CRUD (Create, Read, Update, Delete) operations on student records stored in a MySQL database.

Technologies Used
Java: Programming language used for the application logic.
JDBC: Java Database Connectivity for interaction with the MySQL database.
MySQL: Relational database management system used to store student records.
Scanner: Java Scanner class for user input from the console.
Features
Add Student: Add a new student record to the database.
Update Student: Modify an existing student record.
Delete Student: Remove a student record from the database.
Get All Students: Retrieve and display all student records from the database.
Get Student by ID: Retrieve and display a specific student record by ID.
Delete All Students: Delete all student records from the database.
Database Setup
The application requires a MySQL database to store student records. The following steps guide you on how to set it up:

1. Create a MySQL Database
Create a database named studentdb:

CREATE DATABASE studentdb;
2. Create the Student Table
Create the student table in the studentdb database:

CREATE TABLE student (
    id INT NOT NULL,
    name VARCHAR(45) NOT NULL,
    age INT,
    gender VARCHAR(45),
    phno BIGINT,
    PRIMARY KEY (id)
);
Setup Instructions
To set up and run this project locally, follow the steps below:

Prerequisites
Java 8 or higher installed on your machine.
MySQL database set up locally or remotely.
JDBC Driver for MySQL should be included in your project dependencies.
Steps to Run:
Clone the repository:

git clone https://github.com/KIRAN270-debug/Student-JDBC-Project.git
Navigate to the project directory:

cd Student-JDBC-Project
Open the project in your preferred Java IDE (e.g., Eclipse, IntelliJ IDEA).

Ensure the MySQL server is running and the studentdb database is created as described above.

Run the Student.java class to start the application. The menu will allow you to interact with the database using various operations.

Usage
Once the application is running, you will be presented with a menu in the console. The available options are:

1. Add Student
2. Update Student
3. Delete Student
4. Get All Students
5. Get Student by ID
6. Delete All Students
7. Exit
Select the corresponding number to perform an action.

Example
Here is an example of how the application works:

Adding a student:

Enter the student ID, name, age, gender, and phone number when prompted.
Updating a student:

Enter the student ID to update, and then select which detail to update (ID, Name, Age, Gender, or Phone Number).
Deleting a student:

Enter the student ID and type confirm to delete the student record.
Contributing
Contributions to the project are welcome! Feel free to fork the repository, submit pull requests, or open issues.

Contact
Author: KIRAN SEBASTIAN
GitHub: KIRAN270-debug
