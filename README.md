# Travel & Tourism Management System – Backend

## Overview
This is the backend for a Travel & Tourism Management System built with Node.js, Express.js, MongoDB, and Mongoose. It provides user authentication, agency management, tour packages, and booking features using a clean and simple backend structure.

## How to Run
1. Go to the backend folder
cd backend

2. Install Dependencies
npm install

3. Create a .env file and add:
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000

4. Start the Server
npm start
(Or run node server.js)

## Folder Structure
/backend
  /api
    /controllers
    /middleware
    /models
    /routes
  package.json
  package-lock.json
  server.js

## API Routes

### Users – /api/users
POST /register
POST /login
GET /profile

### Agencies – /api/agencies
POST /create
GET /all

### Bookings – /api/bookings
POST /create
GET /user/:id

### Packages – /api/packages
POST /create
GET /all

## Features
- JWT authentication
- Simple and clean REST API
- Mongoose schema validation
- Proper routing and controllers
- Stable responses and error handling

## Author
Sneha – Backend Developer (Node.js | MongoDB)
