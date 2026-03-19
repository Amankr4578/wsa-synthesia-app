# 🎵 WSA Synthesia App

**WSA Synthesia** is a modern **full-stack music streaming application** built using the **MERN stack**.It allows users to discover music, play songs in real time, manage favourites, and enjoy a smooth audio experience with authentication and secure user profiles.

Songs are fetched using the **Jamendo API**, while user data, favourites, and authentication are handled through a custom backend.

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://cdn.worldvectorlogo.com/logos/react-2.svg" alt="React" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/redux.svg" alt="Redux Toolkit" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/tailwind-css-2.svg" alt="TailwindCSS" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" alt="Node.js" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/express-109.svg" alt="Express.js" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/mongodb-icon-1.svg" alt="MongoDB" height="40"/>
</p>

---

## ✨ Key Features

 

- **🔐 Authentication System** 
  - Signup & Login with JWT
  - Forgot Password & Reset Password via email (Mailtrap)
  - Edit Profile (name, avatar, password)
- **🎶 Music Player** 
  - Play / Pause / Next / Previous
  - Seek bar with real-time progress
  - Loop & Shuffle (mutually exclusive logic) etc..
- **❤️ Favourites Management** 
  - Add / Remove songs from favourites
  - Persistent favourites stored in MongoDB
  - Dedicated favourites view
- 🔍 Search & Browse
  - Search songs via Jamendo API
  - Tag-based playlists

---
## Screenshot:
![App Screenshot](frontend/public/assets/readme-img.png)

**Live Demo** : [Click here to view the app](https://wsa-synthesia-app.netlify.app/)

---

## 📁 Folder Structure
├── frontend  
└── backend  

- **frontend/** → React app with Reduxjs/toolkit, TailwindCSS.  
- **backend/** → Node.js & Express server,MongoDB.  

---

## 📄 License
© 2025 All rights reserved.
