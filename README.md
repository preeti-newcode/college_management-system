📘 College Management System – SQL Database Project

This project involves the creation and population of a structured relational database designed to manage core aspects of a college hostel system. The database is implemented using MySQL and includes four interrelated tables: student, room, complaints, and fee. The design emphasizes data integrity, normalization, and real-world use cases such as room allocation, complaint tracking, and fee management.

🛠️ Key Features
🔹 student Table
Stores detailed student information including ID, name, course, department, contact details, and room assignment.

Ensures data accuracy with constraints like:

PRIMARY KEY on studId

UNIQUE constraint on phoneNo

FOREIGN KEY referencing room(roomId)

🔹 room Table
Tracks room availability, capacity, and pricing.

Fields include roomType, availability, and number of beds.

Used for room assignment in the student table via roomId.

🔹 complaints Table
Allows students to lodge complaints related to specific issues such as hostel, water, or electricity.

Uses an ENUM data type for the reletedTo field to enforce valid categories.

Includes complaint status tracking (pending, resolved, etc.).

FOREIGN KEY links each complaint to a student.

🔹 fee Table
Manages student fee records including total fees, amount paid, and payment status (paid or due).

Tied to the student table via a foreign key relationship.

🧪 Sample Data
Each table is populated with realistic sample records to simulate a working environment.

Includes various combinations of paid/due status, available/full rooms, and complaint resolutions.

✅ Learning Outcomes
Practical application of SQL DDL and DML commands.

Mastery of foreign keys, primary keys, and constraints.

Experience with data relationships and enforcing referential integrity.

Realistic understanding of how to design a small-scale management system using relational databases.

