# Syntecxhub User Management System

A RESTful User Management API developed as part of the **Syntecxhub Web Development Internship Program**.

The project provides user registration, login, authentication, and CRUD (Create, Read, Update, Delete) operations for managing users.

## Project Overview

The User Management System is a backend REST API built with Node.js and Express.js.

It uses MongoDB with Mongoose for data storage and JWT (JSON Web Token) for authentication.

### Main Features

- User registration
- User login
- Password hashing using bcrypt
- JWT-based authentication
- Create users
- Get all users
- Get a single user
- Update users
- Delete users
- Input validation
- Protected API endpoints
- MongoDB database integration

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcryptjs
- dotenv
- Postman

## Project Structure

```text
Syntecxhub_User_Management_System/
│
├── middleware/
│   └── authMiddleware.js
│
├── models/
│   └── User.js
│
├── routes/
│   ├── authRoutes.js
│   └── userRoutes.js
│
├── .env
├── .gitignore
├── package.json
├── package-lock.json
├── server.js
└── README.md