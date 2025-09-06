# WanderLust - Major Project

## 🌍 Project Overview
**WanderLust** is a travel management web application that allows users to explore destinations, manage bookings, and create personalized travel itineraries. Built with **Node.js**, **Express.js**, **MongoDB**, and **EJS**, it features user authentication, session management, and dynamic views.

---

## 🛠 Features

- User authentication (signup/login) using **passport-local-mongoose**
- Browse and search travel destinations
- Manage bookings and travel plans
- Dynamic views with **EJS** templates
- RESTful routing with **method-override**
- Environment configuration using **dotenv**

---

## ⚡ Tech Stack

| Layer             | Technology/Package                  |
|------------------|------------------------------------|
| Backend           | Node.js, Express.js                |
| Database          | MongoDB, Mongoose                  |
| Authentication    | Passport.js, passport-local-mongoose |
| Frontend          | EJS, HTML, CSS                     |
| Utilities         | dotenv, method-override, ejs-mate  |
| Dev Tools         | Nodemon                            |

---

## 📂 Installation & Setup

1. **Clone the repository:**

git clone <your-repo-link>
cd WanderLust-Major-Project-main
Install dependencies:

npm install
If any module is missing, install manually:

npm install dotenv mongoose passport-local-mongoose method-override ejs-mate
Create a .env file in the root folder:

DB_URL=<your-mongodb-connection-string>
SECRET=<your-session-secret>
PORT=3000
Start the server:

nodemon app.js

Access the app:
Open your browser at http://localhost:3000

## 🔧 Usage
Sign up or log in to access personalized features

Browse destinations, make bookings, and manage your trips

Admin can manage destinations and bookings (if implemented)

## ⚠️ Troubleshooting
Module not found errors:
Install missing packages with:

npm install <module-name>
Database connection issues:
Ensure MongoDB is running and DB_URL in .env is correct.

## 📄 License
This project is for educational purposes. Feel free to use and modify it.
