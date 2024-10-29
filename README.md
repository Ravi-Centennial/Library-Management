# Library-Management
📚 Library Management System
Welcome to the Library Management System! This project simplifies managing library data by handling operations like adding, updating, deleting, and viewing records—all powered by Python and MySQL. Let's make library management efficient and fun!

🧰 Features
Add New Books: Easily add records for new books.
Update Information: Modify existing records as needed.
View Books: Display all available books in the library.
Delete Records: Remove outdated or incorrect book records.

🚀 Getting Started
Prerequisites
Make sure you have:

Python (version 3.x recommended)
MySQL and MySQL Connector package for Python

Installation
Clone the Repository
git clone https://github.com/yourusername/library-management-system.git

Navigate to the Directory
cd library-management-system

Install MySQL Connector
pip install mysql-connector-python

Setup MySQL Database
Login to MySQL and create a database:
CREATE DATABASE library_db;

USE library_db;
Run the provided SQL script to set up tables for the project.

Configuration
Open config.py (or similar file) and set your MySQL login credentials:
host = "localhost"
user = "root"
password = "root"
database = "library_db"

📖 Usage Guide
Step 1: Start the Program
Run the Python script:

python library_management.py

Step 2: Follow the Prompts
You'll see fun prompts guiding you through each action:

Type 1 to add a new book!
Type 2 to update book details!
Type 3 to view the library's catalog!
Type 4 to delete a book (hopefully not your favorite one! 😉).

💡 Future Enhancements
User Authentication: Add login features for administrators.
Search Functionality: Find books by author or title.
Interactive GUI: A more intuitive graphical interface.

🤝 Acknowledgments
Thanks to my senior students who helped me to complete this project.
