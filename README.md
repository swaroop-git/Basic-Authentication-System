## 🔐 Authentication System (Node.js + Express + MongoDB + JWT)

A simple authentication system built with **Node.js**, **Express**, **MongoDB**, and **JWT (JSON Web Tokens)**.  
This project demonstrates secure user registration, login, and protected routes using token-based authentication.

---

# 📂 Basic folder structure
Basic-Authentication-System/
├── server.js
├── config/
│   └── db.js
├── models/
│   └── User.js
├── routes/
│   └── auth.js
├── middleware/
│   └── authMiddleware.js
└── .env

---

## 🚀 Features
- User **registration** with hashed passwords (bcrypt)
- User **login** with JWT token generation
- **Protected routes** accessible only with valid tokens
- **Token expiration** for added security
- Environment variable support with **dotenv**
- Modular project structure for scalability

---

## 🛠 Tech Stack
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT (jsonwebtoken), bcrypt
- **Environment Config:** dotenv

---