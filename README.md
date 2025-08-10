# Wellness App

A wellness session management platform that allows users to register, log in, create, publish, and join wellness sessions.  
Built with **Vite + React.js** for the frontend and **Node.js + Express** for the backend, using **MongoDB** as the database.

---

## 📂 Project Structure

wellness-app/
│
├── backend/ # Node.js + Express backend
├── public/ # Public assets for frontend
├── src/ # React frontend source code
├── .gitignore
├── index.html # Frontend entry
├── package.json # Frontend dependencies
├── vite.config.js # Vite configuration
└── README.md


## 🚀 Features

- User Registration & Login
- Session Creation & Publishing
- Session Listing & Management
- Secure Authentication (JWT)
- API Communication with Backend
- Responsive UI

---

## ⚙️ Tech Stack

- **Frontend:** React.js (Vite), TailwindCSS (if used), Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Other:** dotenv, bcrypt

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/wellness-app.git
cd wellness-app


2️⃣ Backend Setup
cd backend
npm install
Create .env file inside backend/ with:
----------------------------------------------
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
-----------------------------------------------

Run backend:
npm start
Backend will run on http://localhost:5000

3️⃣ Frontend Setup
From the project root (where vite.config.js is):
npm install
(Optional) Create .env file at the root if you have API base URL:
---------------------------------------------------
VITE_API_URL=http://localhost:5000
Run frontend:
----------------------------------------------------
npm run dev
Frontend will run on http://localhost:5173 (Vite default).


🛠 How to Run the App
------------------------------
Start backend:
cd backend
npm start
------------------------------
Start frontend in another terminal:
npm run dev
Open http://localhost:5173 in your browser.

📌 Notes
Ensure MongoDB is running (locally or via MongoDB Atlas).

Keep .env files private; they are already ignored in .gitignore.

For production deployment, set up environment variables accordingly.

📄 License
This project is for internal use and demonstration purposes only.
---


---

Since you’re using **Vite** and the backend is separate, this README will make it crystal clear for the company how to set up and run both parts.  

I can also **add example API endpoints** and responses to the README so they can test the backend immediately without running the frontend. That would make it even more complete.


