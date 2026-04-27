# 🏥 Digital Hospital Management System

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application designed to manage hospital operations efficiently.  
The system allows patients to book appointments, while administrators manage doctors, users, and appointments through a secure dashboard.

---

## 🚀 Features

### 👤 Patient
- User Registration & Login
- Book Appointments
- Send Messages to Admin
- View Doctors by Department

### 👨‍💼 Admin Dashboard
- Admin Authentication (JWT-based)
- Add / Manage Doctors
- View & Manage Appointments
- Handle Patient Messages
- Role-Based Access Control

---

## 🧠 Key Highlights

- 🔐 JWT Authentication with HTTP-only Cookies
- 🧩 Role-Based Authorization (Admin / Patient)
- ☁️ Cloud Image Upload (Cloudinary)
- ⚡ REST API Architecture
- 📦 MongoDB Database Integration
- 🖥️ Separate Admin Dashboard

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- Axios
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Security & Utilities
- JWT Authentication
- Cookie Parser
- CORS
- Express File Upload

### Cloud
- Cloudinary (Image Storage)

---

## 📁 Project Structure
Digital-Hospital/
│
├── frontend/ # Patient Interface (React)
├── backend/ # API Server (Node + Express)
└── dashboard/ # Admin Panel (React)



---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/Digital-Hospital.git
cd Digital-Hospital


2️⃣ Backend Setup

cd backend
npm install

Create .env file:

MONGO_URI=mongodb://127.0.0.1:27017/DIGITAL_HOSPITAL
PORT=5000
JWT_SECRET=your_secret_key

Run backend:

node server.js


3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


4️⃣ Dashboard Setup
cd dashboard
npm install
npm run dev


🌐 Application URLs
Frontend (Patient): http://localhost:5173

Dashboard (Admin): http://localhost:5174

Backend API: http://localhost:5000


🧪 Demo Flow

Register as Patient
Login and Book Appointment
Login as Admin (Dashboard)
Approve/Reject Appointment

🎯 Future Enhancements

Doctor Login System
Online Payment Integration
Real-time Notifications
Appointment History Tracking
AI-based Doctor Recommendation


📌 Conclusion

This project demonstrates a real-world healthcare system using the MERN stack with secure authentication, scalable architecture, and role-based access control.

👨‍💻 Author

Sunny Yadav