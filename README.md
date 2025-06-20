# React + MongoDB Atlas CRUD App with Authentication

This full-stack application enables users to **sign up**, **log in**, and **view a list of registered users**. Built using **React.js** for the frontend and **Express.js + MongoDB Atlas** for the backend, the project demonstrates basic **CRUD operations** and **JWT-based authentication**.

---

## 🌟 Features

- 🔐 User Authentication (JWT)
- 📝 Sign Up and Login
- 🚪 Secure Sign Out
- 👥 Public User List
- ☁️ MongoDB Atlas for cloud data storage

---

## 🛠 Tech Stack

- **Frontend**: React.js, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT, bcrypt
- **Dev Tools**: Postman, VS Code

---

## 📁 Project Structure

```text
Lab_12/
├── client/                 # React frontend
│   └── src/
│       ├── components/     # UI Components
│       ├── pages/          # Auth + User List
│       └── App.js
│
├── server/                 # Express backend
│   ├── models/             # MongoDB schemas
│   ├── routes/             # API routes
│   ├── controllers/        # Business logic
│   ├── middleware/         # Auth checks
│   └── server.js
│
├── .env                    # Environment variables
├── README.md               # Project documentation
└── package.json            # Project dependencies
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Lab_12.git
cd Lab_12
```

### 2. Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside `/server`:

```
PORT=5000
MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_secret_key
```

Run the server:

```bash
npm run dev
```

### 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```

App will run on: `http://localhost:3000`

---

## 🧪 API Overview

| Method | Endpoint          | Description              |
|--------|-------------------|--------------------------|
| POST   | /api/auth/signup  | Register new user        |
| POST   | /api/auth/login   | Login and get JWT token  |
| GET    | /api/users        | Public list of all users |

---




