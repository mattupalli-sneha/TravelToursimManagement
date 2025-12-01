Travel & Tourism Management System (MERN)

This is a simple Travel & Tourism Management System built using the MERN stack (MongoDB, Express, React, Node.js).
The project contains:

backend → All APIs, routes, controllers, MongoDB models

frontend → React user interface for users and agencies

This system allows users to browse travel packages, make bookings, and agencies to manage their dashboards.

⭐ Features

User Signup & Login

Agency Login & Dashboard

Travel Packages (title, price, days, location, images)

Booking creation

REST API with Express

React Frontend for UI

📁 Project Structure
backend/
  controllers/
  middleware/
  models/
  routes/
  server.js
  package.json

frontend/
  public/
  src/
    Agency.js
    AgencyDashboard.js
    Login.js
    Signup.js
    Home.js
    many more files...
  package.json

⚙️ Requirements

Node.js

npm

MongoDB (Local or Atlas)

🔧 How to Run the Project
1. Clone the Repository
git clone <your-repo-url>
cd your-folder

2. Setup Backend
cd backend
npm install


Create a .env file inside the backend folder:

MONGO_URI=your_mongodb_url
PORT=5000
JWT_SECRET=anythingsecret


Start backend:

npm run dev

3. Setup Frontend
cd frontend
npm install
npm start


Frontend runs at: http://localhost:3000

Backend runs at: http://localhost:5000

🛣️ API Routes (Examples)
Users
POST /api/users/signup
POST /api/users/login

Agencies
GET /api/agencies
GET /api/agencies/:id

Bookings
POST /api/bookings/create

🧪 Technologies Used

MongoDB

Express.js

React.js

Node.js

Mongoose

👨‍💻 Contributors

Sneha

Sankar

Charan

📜 License

This project is for academic and learning purposes.
