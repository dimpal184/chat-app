# 💬 Real-Time Chat App  

A **full-stack real-time chat application** built with **MERN (MongoDB, Express, React, Node.js)**, **Socket.io**, and **TailwindCSS**.  
It allows users to sign up, log in, and chat instantly with others, with online status indicators and smooth UI.  

---

## 🚀 Features  

- 🔑 **User Authentication & Authorization** – Secure login/signup with JWT  
- 💬 **Real-Time Messaging** – Powered by Socket.io  
- 👥 **Online User Status** – See who is currently online  
- 🖥️ **Responsive UI** – Works seamlessly on all devices  
- 🌐 **Global State Management** – Using Zustand  
- 🛠 **Error Handling** – On both client & server  
- 📦 **Production Ready** – Easily deployable  

---

## 🛠 Tech Stack  

- **Frontend:** React, TailwindCSS, DaisyUI, Zustand  
- **Backend:** Node.js, Express.js, JWT Authentication  
- **Database:** MongoDB  
- **Real-time:** Socket.io  

---

## ⚙️ Setup Instructions  

### 1️⃣ Create a `.env` file  

```ini
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

NODE_ENV=development

2️⃣ Install Dependencies
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

3️⃣ Build the App
npm run build

4️⃣ Start the App
npm start

🔧 My Modifications

Customized the UI design and styles

Updated README and documentation

Setup project with my own database & deployment

📜 License

This project is licensed under the MIT License.
Copyright (c) 2024 Burak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

```
