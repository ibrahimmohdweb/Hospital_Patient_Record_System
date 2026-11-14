@@ -1 +1,47 @@
# Hospital_Patient_Record_System
# Hospital_Patient_Record_System
📌 Internship Project
This project is a **Hospital Patient Record Management System** developed using **Java** and **MySQL**.  
It allows hospitals to store, manage, and update patient records securely.

🚀**Features**
- Add new patient records
- View patient details
- Update medical history
- Delete patient records
- Secure data storage using MySQL
- Menu-driven console interface

🛠 Technologies Used
- Java
- MySQL
- JDBC
- OOP Concepts

 ⚙️ How to Run
1️⃣ Install Requirements
- Install Java (JDK 8 or above)
- Install MySQL
- Install MySQL Connector (JDBC Driver)
2️⃣ Create Database
```sql
CREATE DATABASE hospital_db;
USE hospital_db;
CREATE TABLE patients (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50),
    age INT,
    disease VARCHAR(100),
    medical_history VARCHAR(255));
3️⃣ Update Database Credentials
Edit username and password inside Java file.
4️⃣ Run Program
Compile and run:
javac HospitalSystem.java
java HospitalSystem
🎯 Learning Outcomes:
Understanding database connectivity using JDBC
Implementing CRUD operations
Applying Object-Oriented Programming concepts
Handling user input and exceptions
👩‍💻 Author
Mohammed Ibrahim
Handling user input and exceptions
👩‍💻 Author
Ishra Shameen
