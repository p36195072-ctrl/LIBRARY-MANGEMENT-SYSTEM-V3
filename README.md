Library Management System V3

An intermediate Python project that demonstrates how to build a Library Management System with permanent JSON storage and book management features.

📌 Description

This project allows users to:

Add new books
Store author information
Search books
View all books
Delete books
Prevent duplicate book entries
Save data permanently
Load data automatically

All library records are stored in lib.json, so books remain available even after the program is closed.

🧠 Concepts Used

Python Functions
Dictionaries
Nested Dictionaries
JSON Storage
File Handling
json.load()
json.dump()
User Input
Conditional Statements
Loops
CRUD Operations
Data Persistence

✨ Features

✅ Add Books

✅ Prevent Duplicate Books

✅ Search Books

✅ View Individual Book

✅ View All Books

✅ Delete Books

✅ Automatic JSON Loading

✅ Automatic JSON Saving

✅ Total Book Counter

📂 Files

library_manager_v3.py
lib.json

💻 Stored Information

Each book record stores:

Book Name
Author Name

Example:

{
    "Python Crash Course": {
        "book name": "Python Crash Course",
        "author name": "Eric Matthes"
    },
    "Clean Code": {
        "book name": "Clean Code",
        "author name": "Robert C. Martin"
    }
}

▶️ Example Output

=== LIBRARY ===

1. Add Book
2. View Book
3. View All Books
4. Delete Book
5. Exit

Total Books: 2
