# CODTECH-TASK-1
Name -AbhishekBarla
Company- CODTECH IT SOLUTION
Intern Id-CT6WDS438
Duration- June to July
Mentor- M.Santhosh Kumar


Overview of libary Management System

Library Management System (LMS) Project Description

Overview

The Library Management System (LMS) is a Python-based project that aims to provide a simple and efficient way to manage a library's collection of books. The system allows users to perform various operations such as adding, removing, viewing, issuing, and returning books.

Features

Add Book: Allows users to add a new book to the library's collection by providing the book's title and author.
Remove Book: Enables users to remove a book from the library's collection by providing the book's title.
View Books: Displays a list of all books in the library's collection, including their titles and authors.
Issue Book: Allows users to issue a book to a borrower by providing the book's title.
Return Book: Enables users to return a book to the library's collection by providing the book's title and author.
Exit: Allows users to exit the system.
Technical Details

The project is written in Python 3.x.
The system uses a dictionary to store the library's collection of books, where each book is represented by a key-value pair (title-author).
The system uses a simple text-based interface to interact with users.
The project consists of a single Python file (lms.py) containing the Library class and the main function.
Class Description

The Library class represents the library's collection of books and provides methods to perform various operations on the collection. The class has the following attributes and methods:

books: a dictionary representing the library's collection of books.
add_book(title, author): adds a new book to the library's collection.
remove_book(title): removes a book from the library's collection.
view_books(): displays a list of all books in the library's collection.
issue_book(title): issues a book to a borrower.
return_book(title, author): returns a book to the library's collection.
Main Function

The main function is the entry point of the program. It creates an instance of the Library class and provides a simple text-based interface to interact with users. The function uses a while loop to repeatedly prompt users to choose an option from the menu until they choose to exit.

Example Use Cases

Adding a new book:
User chooses option 1 (Add Book) and enters the book's title and author.
The system adds the book to the library's collection and displays a confirmation message.
Issuing a book:
User chooses option 4 (Issue Book) and enters the book's title.
The system checks if the book is available and issues it to the borrower if available.
Returning a book:
User chooses option 5 (Return Book) and enters the book's title and author.
The system returns the book to the library's collection and displays a confirmation message.
