# 🚀 Fullstack Setup Practice

This repository is created for **practicing full-stack environment setup** using modern technologies like **Next.js, Node.js, Express, and MongoDB**.

The goal of this repo is **NOT to build a final product**, but to:
- Practice installation
- Understand project structure
- Learn how frontend, backend, and database connect

---

## 🧠 Tech Stack

- ⚛️ Next.js (Frontend)
- 🟢 Node.js (Runtime)
- 🚂 Express.js (Backend)
- 🍃 MongoDB (Database)

---

## 📁 Project Structure
fullstack-setup-practice/
│
├── frontend/ # Next.js app
├── backend/ # Node + Express server
└── README.md

---

## ⚙️ Setup Guide (Step-by-Step)

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ManthanThakor/fullstack-setup-practice.git
cd fullstack-setup-practice
```

### 2️⃣ Backend Setup (Node + Express)

cd backend
npm init -y
npm install express mongoose cors dotenv
npm install nodemon --save-dev

Create server.js:

const express = require("express");
const app = express();

app.get("/", (req, res) => {
  res.send("Backend running 🚀");
});

app.listen(5000, () => console.log("Server running on port 5000"));

Run server:

npx nodemon server.js

### 3️⃣ Frontend Setup (Next.js)
cd ../
npx create-next-app@latest frontend
cd frontend
npm run dev

Open:

http://localhost:3000

### 4️⃣ MongoDB Setup

Install MongoDB locally OR use MongoDB Atlas
Create a database
Get connection string

Example .env in backend:

MONGO_URI=your_connection_string
PORT=5000

---

## 🔄 What You Will Practice

Setting up backend server
Creating API routes
Connecting MongoDB
Running frontend + backend together
Environment variables handling
Folder structure understanding

---

## 🎯 Purpose

This project is purely for learning & repetition.

You can:

Delete and rebuild multiple times
Try different setups
Practice debugging errors
📌 Future Practice Ideas
Connect frontend with backend API
Add CRUD operations
Add authentication
Deploy project

---

## 👨‍💻 Author

Manthan Thakor

---

## ⭐ Note

This is a practice repository, not a production-ready project.

---

## 🔥 Small Pro Tip

Keep this repo as your **reset lab**:
- Break things ✔️  
- Fix errors ✔️  
- Repeat setup ✔️  

That’s how you actually master full-stack 💯

---

If you want next:
👉 I can :contentReference[oaicite:2]{index=2}  
👉 or **:contentReference[oaicite:3]{index=3}**

Just tell 😎
::contentReference[oaicite:1]{index=1}