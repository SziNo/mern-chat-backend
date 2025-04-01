# MERN Chat - Backend

## 📌 Description

This project is the backend for a real-time chat application built with the MERN stack. It provides authentication, messaging, and database integration using MongoDB, Express.js, and Socket.io.

## 🌐 Live Project

- **Backend URL**: [https://mern-chat-backend-j0dv.onrender.com/](https://mern-chat-backend-j0dv.onrender.com/)
- **Frontend GitHub**: [https://github.com/SziNo/mern-chat-frontend](https://github.com/SziNo/mern-chat-frontend)
- **Frontend élő URL**: [https://mern-chat-frontend-lemon.vercel.app/](https://mern-chat-frontend-lemon.vercel.app/)

## 🚀 Tech Stack

This project utilizes the following technologies:

- **MongoDB Atlas & Mongoose**: NoSQL database & ODM.
- **Express**: Node.js backend framework.
- **JWT**: Authentication mechanism.
- **Socket.io**: Real-time communication via WebSockets.
- **Cloudinary**: Image storage for user profile pictures.

## 📑 API Endpoints

#### Authentication

- **POST** `/api/auth/signup` – Register a new user.
- **POST** `/api/auth/login` – User login.
- **POST** `/api/auth/logout` – User logout.

#### Messaging

- **GET** `/api/messages/users` – Fetch users for the sidebar.
- **GET** `/api/messages/:id` – Retrieve messages for a conversation.
- **POST** `/api/messages/send/:id` – Send a new message.
