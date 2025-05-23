# College Event Management System

A full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) for managing college events.

## Features

- User authentication (Register/Login)
- Create, read, update, and delete events
- Event filtering and search
- Responsive UI with Tailwind CSS
- Image upload support
- Protected routes for authenticated users

## Project Structure

```
college-event-management/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       └── utils/
└── server/                 # Node.js backend
    ├── config/
    ├── controllers/
    ├── middleware/
    ├── models/
    └── routes/
```

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. Create a .env file in the server directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/college_events
   JWT_SECRET=your_jwt_secret
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd server
   npm run dev

   # Start frontend server
   cd ../client
   npm start
   ```

## API Endpoints

- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user
- GET /api/events - List all events
- POST /api/events - Add a new event
- GET /api/events/:id - Get a specific event
- PUT /api/events/:id - Update an event
- DELETE /api/events/:id - Delete an event

## Technologies Used

- Frontend:
  - React.js
  - React Router DOM
  - Axios
  - Tailwind CSS
  - JWT Authentication

- Backend:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JWT
  - Bcrypt
  - Multer (for file uploads) 


  cd server
  npm install
  npm run dev

  cd client
  npm install
  npm start#   C o l l e g e _ e v e n t _ m a n a g e m e n t  
 