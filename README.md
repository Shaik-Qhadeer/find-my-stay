# 🏡 FindMyStay — Backend

FindMyStay is a backend service for a room and home rental platform. It enables hosts to manage their property listings and users to browse and favorite available homes. Built with Node.js and Express, this project connects to a MongoDB database and implements authentication, authorization, and CRUD operations.

🔗 **Live API Endpoint:** [https://findmystay-2guh.onrender.com](https://findmystay-2guh.onrender.com)

---

## ✨ Features

### 🧑‍💼 Host Features:
- Register and login as a host
- Add new home listings
- Edit or delete existing listings
- View all homes uploaded by the host

### 👥 User Features:
- Register and login as a user
- Browse all homes
- View detailed home info
- Mark/unmark homes as favorites

---

## 🔧 Tech Stack

- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for Authentication
- **Tailwind CSS** (for styling if frontend is attached later)
- Deployed on **Render**

---

## 📁 Folder Structure

```bash
find-my-stay/          # Main backend code         
    ├── app.js               # Entry point
│   ├── routes/              # All route handlers
│   ├── controllers/         # Business logic
│   ├── models/              # Mongoose schemas
│   ├── middleware/          # JWT auth, error handling
│   └── views/               # Tailwind input (if applicable)
│
├── public/                  # Static files and CSS output
├── .env                     # Environment variables (not pushed)
├── .gitignore
├── README.md
└── package.json
