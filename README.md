# Backend

This is the backend server for a full-stack application. It is built using **Node.js**, **Express.js**, and **MongoDB**, with support for **Cloudinary** for media handling and **JWT** for authentication.

## Features

- RESTful API built with Express.js
- User authentication with JSON Web Tokens (JWT)
- Password hashing using bcryptjs
- File uploads using Multer
- Cloudinary integration for media storage
- MongoDB integration using Mongoose
- Environment variable management via dotenv
- CORS support
- Auto-restarting development server with Nodemon

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [npm](https://www.npmjs.com/)
- (Optional) [Cloudinary](https://cloudinary.com/) account for image handling

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Install backend dependencies:

bash
Copy
Edit
npm install
(If applicable) Install frontend dependencies and build frontend:

bash
Copy
Edit
npm run build
Create a .env file in the root directory and add the required environment variables:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret# blog

Scripts
npm run dev: Start the backend server with hot reloading (Nodemon)

npm start: Start the production server

npm run build: Install frontend dependencies and build frontend

Directory Structure
bash
Copy
Edit
project-root/
│
├── backend/
│   └── server.js        # Entry point for backend
│
├── frontend/            # Your frontend code (optional)
│
├── .env                 # Environment variables (not tracked by git)
├── .gitignore
├── package.json
└── package-lock.json
