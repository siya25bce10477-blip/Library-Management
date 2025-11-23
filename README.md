# Library-Management
Project Overview

This project is a based on Library Management System codded in Python.
It allows users to manage library to add books, view all books, search for specific books, issue books to students, return books, and delete books from the system.
The system stores books in Python lists of dictionaries, makes it simple and easy to understand for beginners in learning Python and data structures.

Features
1. Add Book
Allows the user to input: Book ID , Title , Author , Quantity
The book is stored as a dictionary inside the books list.

2. View All Books
Displays each book's ID, title, author, and quantity.
Shows a message if no books are available.

3. Search Book
Searches for a book using its ID.
Displays the book details if found.

4. Issue Book
Checks if the book exists and has available quantity.
Reduces quantity by 1.
Records the issue in issued_books list with student name.

5. Return Book
Verifies if the student truly issued the book.
Removes the record from issued_books.
Increments the book quantity.

6. Delete Book
Delete a book using its ID.
Confirms deletion or shows "Book Not Found".

7. Exit
Ends the program.

Technologies / Tools Used 

This project is built entirely using core Python, making it simple, lightweight, and easy to run without additional installations. It relies on basic Python features such as lists and dictionaries to store book records and issued-book information, allowing for efficient in-memory data management. The program structure is organized through functions, which help separate tasks like adding, issuing, returning, and deleting books. Additionally, the system uses conditional statements, loops, and user input/output functions to control the menu flow and provide an interactive experience. No external libraries or frameworks are used, ensuring the project runs smoothly on any system with Python installed.

Steps to Install & Run the Project

1️)Install Python

2)Create a new .py file

3)Copy the full code

4)Run the program

Instructions for Testing the Project

To test the Library Management System, we will begin by running the program and ensuring the main menu appears correctly. Start by adding a book using the “Add Book” option, entering details such as the book ID, title, author, and quantity; this confirms that book creation and storage work properly. Next, test the “View All Books” option to check whether the newly added book appears in the list. After that, use the “Search Book” feature and enter the same book ID to verify that the search function retrieves accurate details. You can then test the issuing process by selecting “Issue Book,” providing the book ID and a student name, and confirming that the program decreases the book’s quantity and records the issued entry. To validate the return process, use the “Return Book” option with the same book ID and student name and ensure that the system removes the issued record and restores the book quantity. Finally, test the “Delete Book” option to check whether the book can be removed from the system, and confirm everything works smoothly by viewing the book list again or attempting to search for the deleted ID. Completing these steps ensures that each feature behaves as expected.
