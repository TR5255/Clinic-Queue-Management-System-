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
├── backend/
│   ├── controllers/
│   │   └── appointmentController.js   # Appointment logic
│   ├── models/
│   │   ├── Appointment.js             # Appointment schema/model
│   │   └── User.js                    # User/Doctor schema/model
│   ├── routes/
│   │   └── appointmentRoutes.js       # Appointment API routes
│   ├── utils/
│   │   └── sendEmail.js               # Email notifications
│   ├── server.js                      # Express server entry
│   └── config/
│       └── database.js                # MongoDB connection
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── PatientDashboard.js     # Patient UI
│   │   │   └── AdminDashboard.js       # Admin UI
│   │   ├── context/
│   │   │   ├── AuthContext.js          # Authentication state
│   │   │   └── SocketContext.js        # Socket.IO client
│   │   ├── utils/
│   │   │   └── api.js                  # Axios config
│   │   └── App.js                      # Routes & entry point
│   └── package.json
│
├── .env                                # Environment variables
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/appointment-booking-app.git
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

