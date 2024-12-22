# Name: Prajapati Udit Mukesh
# Company: CODTECH IT SOLUTIONS 
# Id: CT6WDS2794
# Domain: Java Programming
# Duration: DECEMBER 12th, 2024 to JANUARY 27th, 2025.
# Mentor: Muzammil Ahmed

# Overview:
The SQL operations performed involve creating and managing a library management system database, including setting up tables for books, members, and transactions, and executing CRUD (Create, Read, Update, Delete) operations on them. The system tracks book details, member information, and borrowing transactions.

# Key Activities:
Database Setup:

Created the LibraryDB database and switched to it.
Table Creation:

Designed and created three tables:
Books with fields for book details and quantity.
Members with member-specific information.
Transactions with borrow/return details and foreign keys linking Books and Members.
Data Insertion:

Added records for books and members.
Logged borrowing transactions in the Transactions table.
Queries and Data Manipulation:

Retrieved a list of active borrow transactions using JOIN operations.
Updated book quantities to reflect borrowing.
Deleted specific transactions and members from the database.

# Technology Used:
Database Management System: MySQL
SQL Features:
Table creation with constraints like AUTO_INCREMENT, PRIMARY KEY, and FOREIGN KEY.
Basic SQL operations: INSERT, SELECT, UPDATE, DELETE.
JOIN operations to link data across tables.

# Key Insights:
# Relational Database Design:
Proper normalization ensures efficient data organization and retrieval. Foreign keys enforce referential integrity between tables.
Transaction Management:

Updates to related entities (e.g., reducing book quantity when borrowed) are crucial for consistency.
Error Avoidance:

Unique constraints (e.g., email in Members) prevent duplicate entries.
Optimization Potential:

Indexing columns like book_id and member_id in Transactions can speed up JOIN operations in larger datasets.
