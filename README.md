<h1 align="center">MERN Stack Project Management Application</h1>
<p align="center">
  <strong>Developed by Amine Ould Medjeber</strong>
</p>

<p align="center">
  <img src="/frontend/public/readme-image.png" alt="Chat App Demo" width="700">
</p>

---

## 🚀 Overview

This project is a modern, responsive Project Management Dashboard application built with React, Vite/React Router v7, TypeScript, and Tailwind CSS v4, utilizing Shadcn UI for pre-built components. It allows users to manage workspaces, projects, and tasks, with features for collaboration and tracking progress. The application works with a NodeJs backend with Express and a MongoDB database.

---

## ✨ Key Features

- Dashboard Overview
- Workspace Management
- Project Management
- Task Management (with comments, Mentions, Reactions, Activity Logs etc)
- User Profile Management
- Notifications
- Authentication (Sign in, Sign up, Forgot password, Email Verification, Reset Password, 2FA)
- Achieved Projects and Tasks
- File Attachment (by file or external url)
- Responsive Desing

---

## ⚙️ Environment Variables Setup

Create a `.env` file inside the **`/backend`** directory with the following configuration:

```bash
PORT=3000
MONGO_URI= your_mongo_uri_here
NODE_ENV= development

JWT_SECRET= your_jwt_secret

SEND_GRID_API= your_resend_api_key
FROM_EMAIL= your_email_from

FRONTEND_URL= http://localhost:5173

ARCJET_KEY= your_arcjet_key
ARCJET_ENV= development
```

Create also `.env` file inside the **`/frontend`** directory with the following configuration:

```bash
VITE_API_URL= http://localhost:5000/api-v1
```



🧩 Installation & Setup

1️⃣ Backend Setup
```bash
cd backend
npm install
npm run dev
```
2️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```



👨‍💻 Author
Amine Ould Medjeber
Full-Stack Developer | Node.js • React • MongoDB • Express.js
📧 [ouldmedjeberamine@gmail.com]
🌐 [www.linkedin.com/in/amine-medjeber]
