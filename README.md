# 📁 Project: `Bckend Project`

This repository contains the complete backend source code for a Node.js and Express-based application with user authentication and contact management features. It uses **MongoDB** as the database and follows a modular and clean architecture for scalability and maintainability.

---

## ✅ Key Features
- RESTful API for user registration, login, and contact CRUD operations.
- JWT-based authentication and token validation.
- Error handling middleware for centralized error responses.
- Modular folder structure separating concerns (routes, controllers, models, etc.).

---

## 📂 Directory Structure & Purpose

- **`README.md`**  
  Basic documentation or project overview.

- **`constants.js`**  
  Stores constant values used throughout the project, such as status codes or static messages.

- **`package.json`**  
  Lists dependencies, scripts, and project metadata.

- **`server.js`**  
  Entry point of the application. Initializes the server, connects to the database, and sets up middleware and routes.

### 📁 config/
- **`dbConnection.js`**  
  Contains logic to connect the Node.js server to the MongoDB database using Mongoose.

### 📁 controllers/
- **`userController.js`**  
  Handles user-related logic such as registration and login.

- **`contactController.js`**  
  Contains functions to create, read, update, and delete contact records.

### 📁 middleware/
- **`errorHandler.js`**  
  Centralized error-handling middleware.

- **`validateTokenHandler.js`**  
  Middleware for verifying JWT tokens to protect private routes.

### 📁 models/
- **`userModel.js`**  
  Mongoose schema and model for user data.

- **`contactModel.js`**  
  Mongoose schema and model for contact information.

### 📁 routes/
- **`userRoutes.js`**  
  Defines user-related API endpoints.

- **`contactRoutes.js`**  
  Defines contact-related API endpoints.

---

## 🛠 Tech Stack
- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for authentication
- **Custom middleware** for validation and error handling
