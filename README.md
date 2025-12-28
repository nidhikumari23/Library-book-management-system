Library Book Management System
Introduction

Library Book Management System is a web-based application developed to manage library activities digitally.
This project helps in maintaining book records, managing users, and tracking book borrowing history in a simple and efficient way.

The system is divided into two main roles: Admin and Student.
Each role has its own dashboard and permissions.
Objective of the Project

The main objective of this project is:

    To reduce manual work in library management
    To manage book records digitally
    To allow students to borrow and return books easily
    To maintain borrowing history properly
    To implement backend concepts learned during academics

User Roles and Functionalities
Admin

Admin is responsible for managing the library. Admin can:

    Login securely
    Add new books
    View all books
    Update book details
    Delete books
    Manage available copies of books
    Logout from the system

Student

Student can use library services digitally. Student can:

    Register and login
    View available books
    Borrow books
    View borrowed book history
    Return books
    Logout from the system

Features of the System

    Role-based authentication (Admin & Student)
    Secure login using JWT authentication
    Book availability management
    Borrow and return system
    Borrow history tracking
    Clean and user-friendly UI
    Proper backend and frontend integration

Technologies Used
Backend

    Node.js
    Express.js
    MongoDB
    Mongoose
    JSON Web Token (JWT)

Frontend

    HTML
    CSS
    JavaScript

Tools

    VS Code
    GitHub
    Postman

Project Folder Structure

Library-Book-Management-System │ ├── backend │ ├── models │ ├── routes │ ├── middleware │ ├── config │ └── server.js │ ├── frontend │ ├── index.html │ ├── admin.html │ ├── student.html │ ├── style.css │ └── script.js │ └── README.md
How to Run the Project
Backend Setup

    Clone or download the project

    Open backend folder in VS Code

    Install required packages:

    Create a .env file and add: MONGO_URI=your_mongodb_connection_string JWT_SECRET=your_jwt_secret

    Start the server:

Frontend Setup

    Open the frontend folder
    Open index.html in browser
    Register or login as Admin / Student

Authentication Flow

    User logs in
    JWT token is generated
    Token is stored in browser localStorage
    Token is sent in API headers for authorization
    Logout clears token from localStorage

Future Enhancements

    Add book return due date and fine calculation
    Improve UI with advanced design
    Add search and filter options
    Add email notification system
    Deploy backend on cloud server

Learning Outcome

This project helped in understanding:

    REST API development
    Authentication and authorization
    MongoDB database operations
    Frontend and backend integration
    Real-world application workflow

Conclusion

Library Book Management System is a simple and effective project that demonstrates full-stack development concepts.
It is useful for academic learning and practical implementation of backend technologies.
Developed By (This project was developed by a team of four members:)

Jyoti Kumari
Nidhi Kumari Priyanshi Agarwal
Palak
3rd Year, Computer Science Engineering
About

