A real-time chat application built using the MERN Stack (MongoDB, Express.js, React, Node.js) with WebSockets for seamless communication.

Features
User Authentication: Secure login and registration system
Real-time Messaging: Instant chat functionality using WebSockets
Private & Group Chats: One-on-one and group conversations
Online Status Indicator: Shows user presence in real-time
Responsive UI: Optimized for both mobile and desktop
Tech Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
WebSockets: Socket.io for real-time communication
Installation & Setup
Clone the repository


cd ChatAPP
Install dependencies

Backend:
npm install
Frontend:
npm install
Set up environment variables

Create a .env file in the server folder and add:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run the application

Start the backend server:
npm start
Start the frontend:
npm start
Usage
Register or log in to the chat application.
Start private conversations or create group chats.
Enjoy real-time messaging with WebSockets.
Future Enhancements
Typing indicators
Message read receipts
Voice and video calls
