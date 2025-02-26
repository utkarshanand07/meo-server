# Meo-Server

Meo-Server is the backend service for the **Meowssenger** real-time chat application. It is built with **Node.js**, **Express.js**, and **Socket.io** for handling real-time messaging, using **MongoDB** as the database and **Cloudinary** for media storage.

This server runs independently but is designed to work with the [Meowssenger client](https://github.com/utkarshanand07/Purrfect).

## 🚀 Features
- WebSocket-based real-time messaging
- User authentication with JWT
- MongoDB for message and user storage
- Cloudinary integration for media uploads
- RESTful API for chat functionality

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Real-time:** Socket.io
- **Database:** MongoDB
- **Cloud Storage:** Cloudinary

## 📂 Setup & Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/utkarshanand07/meo-server.git
cd meo-server
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Setup Environment Variables
Create a `.env` file in the root directory:
```ini
MONGODB_URI=
PORT=
JWT_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

### 4️⃣ Run the Server
```sh
npm run dev  # Development mode
```

For production:
```sh
npm start
```

## 📡 API Endpoints
| Method | Endpoint      | Description          |
|--------|--------------|----------------------|
| POST   | `/api/auth/register` | Register new user |
| POST   | `/api/auth/login`    | Login user |
| GET    | `/api/messages`    | Fetch messages |
| POST   | `/api/messages`    | Send message |

## 🔗 Related Project
Frontend: [Meowssenger Client](https://github.com/utkarshanand07/Purrfect)

## 📜 License
This project is licensed under the **MIT License**.

---
⭐ **If you find this useful, consider giving it a star!** ⭐
