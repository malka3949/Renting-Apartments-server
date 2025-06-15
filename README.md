# 🖥 Real Estate Backend API

## 🔍 Overview

This is the backend of a Real Estate Marketing Website.  
It provides a secure and scalable **REST API** for managing property listings, user authentication, and role-based access.

---

## ✨ Key Features

- 🔐 User registration and login with **bcrypt** password hashing  
- 🛡 Authentication using **JWT (JSON Web Tokens)**  
- 🎯 Role-based access control (Admin / Client)  
- 🏠 Full CRUD operations for property listings  

---

## 🛠 Technologies Used

- **Node.js**  
- **Express.js**  
- **MongoDB + Mongoose**  
- **bcrypt**  
- **jsonwebtoken (JWT)**

---

## ⚙️ Installation & Running

### 1. Navigate to the server folder:
```bash
cd server
```

### 2. Install dependencies:
```bash
npm install
```

### 3. Create a `.env` file with the following:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Start the server:
```bash
npm start
```

---

## 📁 Folder Structure

```
server/
 ├── controllers/     # Route logic
 ├── models/          # Mongoose schemas
 ├── routes/          # API endpoints
 ├── middleware/      # Auth & role checks
 └── server.js        # App entry point
```

---

## 🔐 Security Highlights

- 🔒 Passwords hashed using **bcrypt**
- 🧾 JWT used to protect routes and sessions
- 👥 Role-based access (admin/client)

---

## 📄 License

MIT License

---

> This API is designed to serve as the backend for a full-featured real estate web platform. Easily extendable with dashboards, image uploads, or advanced filtering.
