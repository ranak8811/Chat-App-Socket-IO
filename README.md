# ✨ Full Stack Realtime Chat App ✨

A modern, full-stack realtime chat application built with the **MERN** stack, **Socket.io**, and styled using **TailwindCSS** and **DaisyUI**. It supports real-time messaging, authentication, global state management, and more!

---

## 🌟 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Live Demo](#live-demo)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## 🧩 Introduction

This project is a fully functional real-time chat app that allows users to send instant messages, see online statuses, and manage authentication securely. It leverages modern web technologies to deliver a seamless and dynamic chatting experience.

---

## 🚀 Features

- JWT-based Authentication & Authorization
- Real-time messaging with **Socket.io**
- Online/Offline user status
- Global state management using **Zustand**
- Client and server-side error handling
- Responsive UI with **TailwindCSS** and **DaisyUI**
- Secure password hashing and storage
- Cloud-based media storage with **Cloudinary**
- Modern UX with toast notifications
- Production-ready build scripts

---

## 🛠️ Tech Stack

**Frontend:**

- React
- Axios
- Zustand
- React Router DOM
- Socket.io Client
- React Hot Toast
- TailwindCSS
- DaisyUI
- Lucide React

**Backend:**

- Node.js
- Express.js
- MongoDB with Mongoose
- Socket.io
- JWT for authentication
- Bcrypt.js for password hashing
- Cloudinary for media uploads
- CORS, Dotenv, Cookie-parser

---

## 🌐 Live Demo

Check out the live app here:  
➡️ [Realtime Chat App](https://chat-app-socket-io-dvzk.onrender.com)

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/ranak8811/Chat-App-Socket-IO.git
cd Chat-App-Socket-IO
```

2. **Install backend dependencies:**

```bash
cd backend
npm install
```

3. **Install frontend dependencies:**

```bash
cd ../frontend
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file in the backend directory and add the following:

```plaintext
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

---

## 📦 Usage

**To run the app locally:**

1. Start the backend server:

```bash
cd backend
npm start
```

2. Start the frontend app:

```bash
cd frontend
npm start
```

**To build the frontend app:**

```bash
npm run build
```

---

## 📁 Project Structure

```plaintext
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── lib
│   └── index.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── hooks
│   │   ├── pages
│   │   ├── services
│   │   ├── store
│   │   ├── utils
│   │   └── App.jsx
│   └── tailwind.config.js
├── README.md
└── package.json
```

---

## 🧪 Examples

- **Register and Login**
- **Send and receive instant messages**
- **View online/offline user statuses**
- **Upload media to Cloudinary**
- **Global notifications using Toaster**

---

## 🛠 Troubleshooting

- Ensure MongoDB Atlas is properly connected.
- Make sure your `.env` variables are correct.
- If WebSocket connection issues occur, check CORS settings and socket URL.
- Ensure that Cloudinary credentials are valid for image uploads.

---

## 👨‍💻 Contributors

- [**Md Anwar Hossain**](https://github.com/ranak8811)

---

## 📜 License

This project is licensed under the **MIT License** - feel free to use it for personal and commercial purposes.
