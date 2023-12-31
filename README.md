# REST API Project

This project aims to create a RESTful API using Node.js, Express, and MongoDB with Mongoose for database operations.

# Overview

This API provides functionalities to manage user data. It utilizes CRUD (Create, Read, Update, Delete) operations to handle user information stored in a MongoDB database.

# Features

- GET: Retrieve all users from the database.
- POST: Add a new user to the database.
- PUT: Edit a user by their ID.
- DELETE: Remove a user by their ID.

# Usage

Start the server:

npm start
Use an API development tool like Postman to test the endpoints.

GET: http://localhost:3000/users
POST: http://localhost:3000/users
PUT: http://localhost:3000/users/:id
DELETE: http://localhost:3000/users/:id

Folder Structure

Copy code
├── config/
│ └── .env
├── models/
│ └── User.js
├── server.js
└── ...
