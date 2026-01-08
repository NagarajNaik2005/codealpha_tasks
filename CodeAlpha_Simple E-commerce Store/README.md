🛒 BagsStore - A Simple E-Commerce Store

Full Stack Web Application

A complete Full Stack E-Commerce Website built using HTML, CSS, JavaScript for the frontend and Node.js with Express.js for the backend.
This project was developed as part of the CodeAlpha Full Stack Development Internship.

It allows users to browse products, add them to cart, place orders, and manage accounts with database support.

🚀 Features
👤 User System

User Registration

User Login

Secure authentication using middleware

🛍️ Shopping Features

Product listing

Product detail view

Add to cart

Remove from cart

Update quantities

📦 Order Processing

Checkout system

Order placement

Order storage in database

🛠️ Admin Features

Add products

Edit products

Delete products

Manage orders

🖥️ Tech Stack
Frontend

HTML

CSS

JavaScript

Backend

Node.js

Express.js

Database

MongoDB (using Mongoose)

📂 Project Folder Structure
CODEALPHA_SIMPLE_ECOMMERCE

├── components    → Reusable UI components
├── config        → Database & environment configuration
├── middleware    → Authentication & request handling
├── models        → MongoDB schemas (Users, Products, Orders)
├── public        → Frontend files (CSS, JS, Images)
├── routes        → Express routes (auth, products, cart, orders)
├── seedDB        → Sample data for database
├── views         → EJS / HTML templates
│
├── app.js        → Main server file
├── package.json → Project dependencies
├── README.md    → Project documentation
└── screenshot.png → Project preview

🗄️ Database

This project uses MongoDB to store:

Users

Products

Shopping Cart

Orders

MongoDB is connected using Mongoose, which helps in managing schemas and database operations easily.

🔐 Authentication & Security

Session-based login system

Password hashing

Protected routes using middleware

Only logged-in users can:

Add items to cart

Place orders

🎯 CodeAlpha Internship Task Fulfilled

This project satisfies Task 1: Simple E-commerce Store:

✔ Product Listings
✔ Shopping Cart
✔ Product Details Page
✔ Order Processing
✔ User Registration & Login
✔ Database for users, products, and orders

📸 Project Preview

🧑‍💻 Developer

Name: Nagaraj Naik
Internship: CodeAlpha Full Stack Development
Project: Simple E-Commerce Store

📜 License

This project is created for educational and internship purposes only.