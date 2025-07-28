# 📚 Online Bookstore Management System

This is a web-based application developed using **PHP**, **MySQL**, and **Bootstrap** to manage the operations of an online bookstore. It allows users to browse, view, and purchase books, while providing admins with the ability to manage book inventory and maintain records.

## 💡 Features

- 📖 Browse and view detailed book listings
- 🛒 Add books to cart and proceed to checkout
- 🔍 Filter books by publisher or author
- 🔐 Admin panel for managing books (add/edit/delete)
- 📷 Book images and description display
- 🗂 Organized folder structure for MVC-style separation


## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP (Core)
- **Database:** MySQL
- **UI Components:** JavaScript, Bootstrap


## 🗃️ Database Setup

1. Import the SQL file: `bookstoredb.sql` via **phpMyAdmin**
2. Database name suggestion: `bookstore`
3. Ensure your DB config in `functions/database_functions.php` is:

php
`$conn = mysqli_connect("localhost", "root", "", "bookstore");`

🚀 How to Run

1.Copy the project folder into `C:/xampp/htdocs/`
2.Start Apache and MySQL using XAMPP
3.Import the bookstoredb.sql database

Visit in your browser :-
`http://localhost/bookstore`

📁 Project Structure
bookstore/
├── admin.php
├── book.php
├── books.php
├── cart.php
├── functions/
├── models/
├── template/
├── bootstrap/
└── bookstoredb.sql

