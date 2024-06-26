# Book-store-management-system-

Description:
The Book Store Management System is a simple console-based application written in Java. It allows users to manage a collection of books in a bookstore. Users can add new books, search for books by title, list all available books, and sell books by reducing their quantity.

Features:
Add Book: Allows the user to add a new book to the store.
Search Book: Allows the user to search for a book by its title.
List All Books: Displays all books available in the store.
Sell Book: Allows the user to sell a book by specifying the title and quantity to sell.
Exit: Exits the application.

Classes

Book

Represents a book with the following attributes:

title (String): The title of the book.
author (String): The author of the book.
price (double): The price of the book.
quantity (int): The quantity of the book available in the store.

Methods

Book(String title, String author, double price, int quantity): Constructor to initialize a book.
String getTitle(): Returns the title of the book.
void setQuantity(int quantity): Sets the quantity of the book.
int getQuantity(): Returns the quantity of the book.
String toString(): Returns a string representation of the book.

BookStore

Manages a collection of books using an ArrayList.

Methods:
BookStore(): Constructor to initialize the bookstore.
void addBook(Book book): Adds a book to the bookstore.
Book searchBook(String title): Searches for a book by its title.
void listBooks(): Lists all books in the bookstore.
void sellBook(String title, int quantity): Sells a specified quantity of a book.

BookStoreManagementSystem

Contains the main method to interact with the user through the console.

Methods
public static void main(String[] args): The main method that drives the application.

Usage

1.Compile the Java files:
         javac Book.javaBookStore.
         javaBookStoreManagementSystem.java
2.Run the application:
         java BookStoreManagementSystem
3.Follow the on-screen prompts to add, search, list, or sell books.

Example:

Book Store Management System
1. Add Book
2. Search Book
3. List All Books
4. Sell Book
5. Exit
Enter your choice: 1
Enter title: Java Programming
Enter author: John Doe
Enter price: 29.99
Enter quantity: 10
Book added successfully.

Book Store Management System
1. Add Book
2. Search Book
3. List All Books
4. Sell Book
5. Exit
Enter your choice: 3
Title: Java Programming, Author: John Doe, Price: 29.99, Quantity: 10


License

This project is licensed under the MIT License.

Done By: VarunKumar .D
