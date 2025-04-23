# Prescripto
Prescipto is a full-stack appointment booking system that allows users to register and book appointments with doctors. Admins can manage data, and doctors can view their scheduled appointments. Built using MERN stack and modern web technologies.

# 🩺 Prescipto - Doctor Appointment Booking System

Prescipto is a full-stack web application that streamlines the process of booking and managing medical appointments. Built with the MERN stack (MongoDB, Express.js, React.js, and Node.js), this platform offers tailored interfaces for three types of users: **Admins**, **Doctors**, and **Customers**.

---

## 🚀 Features

### 🔐 Authentication
- Secure login and signup for Admins, Doctors, and Customers
- Role-based access control

### 👨‍⚕️ Doctor Dashboard
- View upcoming appointments
- Manage availability and personal information

### 📅 Customer Portal
- Search and book appointments with available doctors
- View and manage existing bookings

### 🛠️ Admin Panel
- Manage doctor and patient records
- Monitor system activities

---

## 🧰 Tech Stack

- **Frontend:** React.js, Redux (if used), TailwindCSS / Bootstrap (whichever styling tool you used)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Other Tools:** (Mention any tools like Mongoose, Axios, etc.)

---

## 📷 Screenshots

_Add some screenshots or gifs showing the UI for each role — Admin, Doctor, Customer._

---

## 🔧 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/prescipto.git

# Navigate to the project folder
cd prescipto

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Create .env file for backend configuration
touch .env

# Add your environment variables (example below)
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret

# Run the backend
npm start

# Run the frontend
cd ../client
npm start
