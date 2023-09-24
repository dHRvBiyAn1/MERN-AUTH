# MERN Stack User Authentication Project

This is a sample project that demonstrates how to build a user authentication system using the MERN (MongoDB, Express.js, React, Node.js) stack. User authentication is a fundamental feature in many web applications, and this project provides a starting point for implementing it in your own projects.

## Features

- User registration with email verification
- User login with session management
- Password hashing for security
- Protected routes for authenticated users
- User profile management
- Logout functionality

## Technologies Used

- MongoDB: A NoSQL database for storing user data.
- Express.js: A Node.js framework for building the backend server.
- React: A JavaScript library for building the frontend user interface.
- Node.js: A JavaScript runtime for building server-side applications.
- JSON Web Tokens (JWT): For secure authentication.
- bcrypt.js: For password hashing.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your machine.
- MongoDB installed and running.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dHRvBiyAn1/MERN-AUTH.git

2. Navigate to the project directory:
   ```bash
   cd MERN-AUTH

3. Install server Dependencies:
   ```bash
   npm install

4. Install client dependencies:
   ```bash
   cd frontend
   npm install

### Configuration

1. Create a `.env` file in the `root` directory and configure the following variables:
   ```bash
   PORT=5000
   MONGODB_URI=your-mongodb-connection-string
   JWT_SECRET=your-jwt-secret-key

### Running the Application

1. Start server and client using a single command:
   ```bash
   npm run dev

2. Access the application at `https://localhost:5000` in your browser.

### Usage

1. Register a new user account.
2. Login with your credentials.
3. Update your user profile.
4. Logout when you're done.
   




