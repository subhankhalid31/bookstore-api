# Bookstore RESTful API

A simple RESTful API for managing books in a bookstore.

## Features
- Full CRUD operations (Create, Read, Update, Delete)
- MongoDB database with Mongoose
- Clean and organized project structure

## Tech Stack
- Node.js + Express.js
- MongoDB Atlas + Mongoose
- dotenv

## API Endpoints

| Method | Endpoint           | Description                  |
|--------|--------------------|------------------------------|
| POST   | `/books`           | Create a new book            |
| GET    | `/books`           | Get all books                |
| GET    | `/books/:id`       | Get book by ID               |
| PUT    | `/books/:id`       | Update a book                |
| DELETE | `/books/:id`       | Delete a book                |

## How to Run Locally

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install