# User_skills_manager_Projects - MERN Stack CRUD App

A simple **User Skills Manager** web application built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). This project allows users to perform **CRUD (Create, Read, Update, Delete)** operations on user profiles and their associated skills.

---

## 🚀 Features

- 📝 Add new users with their name and skills
- 📄 View a list of all users and their skills
- ✏️ Edit user information and update skills
- 🗑️ Delete a user from the system
- ⚙️ Fully integrated with MongoDB (local or cloud)

---

## 🛠️ Tech Stack

| Frontend       | Backend           | Database         | Tools           |
|----------------|-------------------|------------------|-----------------|
| React.js       | Node.js           | MongoDB          | Postman         |
| Axios          | Express.js        | Mongoose         | Nodemon         |
| React Hooks    | REST API          | MongoDB Atlas    | VS Code         |

---

## 📁 Folder Structure
user-skills-manager/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/ # Components like UserForm, UserList
│ │ ├── App.js
│ │ └── index.js
├── server/ # Node.js backend
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API routes
│ ├── .env # Environment variables
│ └── server.js # Entry point

---

## Backend Setup (Express + MongoDB):
=> cd server
   npm install
## Create a .env file and add:
=> PORT=5000
   MONGO_URI=mongodb://localhost:27017/userSkillsDB  # or MongoDB Atlas URI
## Then run the backend:
=> npm start
   or with nodemon
   npx nodemon server.js

---

## Frontend Setup (React):
=> cd client
   npm install
   npm start

~ THANK YOU ~
