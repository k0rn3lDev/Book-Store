# Bookstore Website

A complete **Bookstore Web Application** built from scratch using only core web technologies (HTML, CSS, JavaScript, Node.js, and MySQL). This project is part of my final coursework for **Web Development** and **Databases** subjects in my Computer Science program.

---

## 🌐 Project Overview

This project is a fully functional online bookstore that allows users to:

- Browse and search for books
- View detailed information about each book
- Register and log in securely
- Purchase books and manage their cart
- Leave ratings and feedback for books

The goal is to build everything from scratch **without using any frontend or backend frameworks or libraries**, to demonstrate mastery of fundamentals.

---

## 🧱 Project Structure

```plaintext
bookstore-project/
│
├── frontend/               # All client-side code (HTML, CSS, JS)
│   ├── assets/             # Static files (images, icons, fonts)
│   ├── css/                # Stylesheets
│   ├── js/                 # Scripts for interactivity and validation
│   ├── index.html          # Homepage
│   ├── books.html          # Book catalog
│   ├── book-details.html   # Individual book details
│   ├── login.html          # Login form
│   ├── register.html       # Registration form
│   └── 404.html            # Error page
│
├── backend/                # Node.js backend logic and APIs
│   ├── controllers/        # Logic handlers for each API route
│   ├── models/             # Database model definitions
│   ├── routes/             # Express routes
│   ├── services/           # Database and business logic
│   ├── config.js           # Environment and DB configuration
│   ├── app.js              # Express app setup
│   └── server.js           # Server entry point
│
├── database/               # SQL and DB-related logic
│   ├── schema.sql          # SQL schema definitions (tables, keys)
│   ├── seedData.sql        # Optional sample data
│   └── db.js               # MySQL connection logic
│
└── README.md               # This file
