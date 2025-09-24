# 🏥 Clinic-Queue-Management-System

A doctor-patient appointment management platform where patients can book, view, and cancel appointments with doctors, while admins can manage doctors and appointments.
Built with **MERN stack (MongoDB, Express, React, Node.js)**, this project provides a scalable backend with a modern frontend interface.

---

## 📌 Features

* 🔐 **Authentication & Authorization** – Secure login/registration with JWT middleware.
* 👨‍⚕️ **Doctor Management** – Doctors can register with specialization.
* 🧑‍🤝‍🧑 **Patient Dashboard** – Patients can view and book appointments.
* 📅 **Appointment System** – Book, view, and cancel doctor appointments.
* 📢 **Real-Time Updates** – Socket.IO notifications for appointment changes.
* 📧 **Email Notifications** – Confirmation & reminders.
* 📊 **Admin Dashboard** – Manage doctors, patients, and appointments.

---

## 📂 Project Structure

```
appointment-booking-app/
├── sad-clinic-backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── appointmentController.js
│   │   ├── authController.js
│   │   └── doctorController.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   ├── errorMiddleware.js
│   │   └── uploadMiddleware.js
│   ├── models/
│   │   ├── Appointment.js
│   │   ├── Doctor.js
│   │   └── User.js
│   ├── routes/
│   │   ├── adminRoutes.js
│   │   ├── appointmentRoutes.js
│   │   ├── authRoutes.js
│   │   └── doctorRoutes.js
│   ├── uploads/
│   │   ├── 1736855079711.jpg
│   │   ├── 1736855080709.jpg
│   │   ├── 1736855081729.jpg
│   │   └── 1736855083747.jpg
│   ├── utils/
│   │   └── generateToken.js
│   ├── .env
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
│
├── sad-clinic-frontend/
│   ├── node_modules/
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── src/
│   │   ├── components/
│   │   │   ├── Footer.js
│   │   │   └── Navbar.js
│   │   ├── context/
│   │   │   ├── AuthContext.js
│   │   │   └── SocketContext.js
│   │   ├── pages/
│   │   │   ├── AdminDashboard.js
│   │   │   ├── BookAppointment.js
│   │   │   ├── DoctorDashboard.js
│   │   │   ├── ForgotPassword.js
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   │   ├── PatientDashboard.js
│   │   │   ├── Register.js
│   │   │   └── ResetPassword.js
│   │   ├── utils/
│   │   │   └── api.js
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── index.css
│   │   └── index.js
│   ├── .gitignore
│   ├── package-lock.json
│   └── package.json
│
├── README.md
├── tailwind.config.js
└── package-lock.json

```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/TR5255/Clinic-Queue-Management-System-.git
cd appointment-booking-app
```

### 2️⃣ Setup backend

cd fsd-clinic-backend
npm install
npm start

### 3️⃣ Setup frontend
cd fsd-clinic-frontend
npm install
npm start

Frontend will run at 👉 `http://localhost:3000`
Backend will run at 👉 `http://localhost:5000`

---

## ⚙️ Tech Stack

* **Frontend:** React, Axios, TailwindCSS, Socket.IO client
* **Backend:** Node.js, Express.js, Socket.IO, Nodemailer
* **Database:** MongoDB with Mongoose
* **Auth:** JWT (JSON Web Tokens)

---
## 📖 Future Enhancements
* 📱 Mobile app version
* 💳 Online payment integration
* 📍 Location-based doctor search
* 🔔 SMS/WhatsApp reminders

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

