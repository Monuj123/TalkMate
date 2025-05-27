# TalkMate
TalkMate is a modern, full-stack chat application built with React, Express.js, Node.js, and MongoDB, enabling both one-to-one and group real-time messaging.

- 🚀 Features
  - 💬 Chat Functionality
    - One-to-One Messaging: Private conversations between two users.
    - Group Chats: Create and manage group conversations with multiple participants.
    - Real-Time Updates: Powered by Socket.IO for instant message delivery.
    - Message History: Previous messages are stored and displayed upon reconnection.

- 🔐 Security & Authentication
  - JWT Authentication: Secure login and registration with JSON Web Tokens.
  - Protected Routes: Only authenticated users can access chats.
  - Password Encryption: User passwords are hashed using bcrypt.
 
- 🛠 Tech Stack
  - Frontend - React.js, Context API, Axios
  - Backend	- Node.js, Express.js
  - Database - MongoDB (Mongoose)
  - Real-Time	- Socket.IO
  - Auth	- JWT, bcrypt
# 📦 Installation
- Prerequisites
  - Node.js (v16+)
  - MongoDB (local or cloud URI)
  - npm or yarn

# Setup Instructions
- Clone the repository
   
       git clone https://github.com/yourusername/TalkMate.git
       cd TalkMate
- Install dependencies

       # Backend setup
      cd server
      npm install
      
      # Frontend setup
      cd ../client
      npm install
- Configure environment variables
   - Create a .env file in the server directory:

          MONGO_URI=your_mongodb_connection_string
          JWT_SECRET=your_jwt_secret_key
          PORT=5000

- Run the application
    - Start the backend server:
      
          cd server
          node index.js
    - Start the frontend development server:
      
          cd ../client
          npm start

