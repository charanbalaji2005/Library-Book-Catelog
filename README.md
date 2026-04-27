# 📚 Library Book Catalog (MERN Stack)

## 🎥 Project Demo

[![Watch the Demo](https://img.youtube.com/vi/o4X8YpwEQWw/0.jpg)](https://youtu.be/o4X8YpwEQWw)

A full-featured **Library Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** with a modern white & blue UI/UX design.

---

## 🚀 Quick Start

### 📌 Prerequisites
- Node.js v16+
- MongoDB (Local / Atlas)

---

### 1️⃣ Install Dependencies

```bash
npm run install-all
```

Or manually:
```bash
cd server && npm install
cd ../client && npm install
```

---

### 2️⃣ Configure Environment

```bash
cd server
cp .env.example .env
```

Update `.env` file:

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

---

### 3️⃣ Seed the Database

```bash
npm run seed
```

---

### 4️⃣ Run the Application

```bash
npm run dev
```

🌐 Frontend: http://localhost:3000  
🔗 Backend API: http://localhost:5000  

---

## 🔑 Login Credentials

| Role   | Email               | Password     |
|--------|--------------------|-------------|
| Admin  | admin@library.com  | admin123    |
| Member | alice@example.com  | password123 |

---

## ✨ Features

### 👤 Member Features
- 🔍 Search, filter, and browse books  
- 📖 Borrow books (max 5, 14 days)  
- 🔄 Renew books (up to 2 times)  
- ✅ Return books online  
- ⭐ Rate and review books  
- 📊 Dashboard (history, active borrows, fines)  
- 💰 Fine tracking (₹5/day)  

---

### 🛠 Admin Features
- 📚 Add, edit, delete books  
- 👥 Manage users  
- 🔄 Manage borrow/return system  
- 📈 Analytics dashboard  
- ⚠️ Track overdue books  

---

## 🗂️ Project Structure

```
library-book-catalog/
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   └── server.js
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── services/
│   │   └── styles/
│   └── public/
└── package.json
```

---

## 🎨 Design

- 🎯 Clean white & blue UI  
- 🔤 Fonts: Plus Jakarta Sans, Sora  
- 📊 Charts: Chart.js  
- 🔔 Notifications: react-hot-toast  

---

## 🔧 API Endpoints

| Method | Route | Description |
|--------|------|-------------|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login |
| GET | /api/books | Get all books |
| POST | /api/books | Add book (admin) |
| POST | /api/borrows | Borrow book |
| PUT | /api/borrows/return/:id | Return book |
| PUT | /api/borrows/renew/:id | Renew book |
| GET | /api/dashboard/admin | Admin stats |
| GET | /api/dashboard/user | User stats |
| POST | /api/reviews | Add review |

---

## 🧠 Concepts Used

- MERN Stack Development  
- REST API Design  
- Authentication (JWT)  
- CRUD Operations  
- React Hooks & Context API  
- Client-Server Architecture  

---

## 💡 Use Cases

- 🎓 Student Mini / Final Year Project  
- 💼 Portfolio Project  
- 🧪 Practice Full Stack Development  

---

## 🙌 Support

If you like this project:
⭐ Star the repo  
📢 Share with others  
🔔 Subscribe on YouTube  

---

## 📜 License

This project is for educational purposes.
