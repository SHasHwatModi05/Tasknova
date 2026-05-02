# 🚀 Tasknova

An end-to-end task and project management application that enables teams to efficiently organize workflows, assign responsibilities, and monitor progress.
Developed with Next.js, MongoDB, and Tailwind CSS, featuring secure authentication and role-based access control.

## 🌐 Live Demo  
👉 tasknova-production-32c5.up.railway.app

---

## 📌 Overview

Tasknova simplifies collaboration between admins and team members by providing a structured workflow:

- Admins manage projects and assign tasks  
- Members track and update their work progress  
- Tasks are organized and monitored efficiently  

---

## ✨ Key Features

### 🔐 Authentication & Security
- JWT-based authentication
- Secure login & registration
- Protected routes and APIs

### 👥 Role-Based Access Control
- **Admin**
  - Create & manage projects
  - Assign tasks to members
  - Delete tasks/projects
- **Member**
  - View assigned tasks
  - Update task status

### 📁 Project Management
- Organize tasks within projects
- Better workflow separation

### 📊 Task Workflow
- Status tracking:
  - 🟡 To Do  
  - 🔵 In Progress  
  - 🟢 Done  
- Real-time updates

### 🎨 UI/UX
- Clean and modern interface
- Glassmorphism design
- Responsive layout
- Built with Tailwind CSS & Lucide Icons

---

## 🛠️ Tech Stack

| Category        | Technology |
|----------------|-----------|
| Frontend       | Next.js 15, React 19 |
| Styling        | Tailwind CSS v4 |
| Backend        | Next.js API Routes |
| Database       | MongoDB (Mongoose) |
| Auth           | JWT (jsonwebtoken) |
| State Mgmt     | Zustand |
| Icons          | Lucide React |

---

## 📂 Project Structure

```bash
team-task-manager/
│
├── app/                     # Next.js App Router
│   ├── (auth)/              # Authentication pages
│   ├── dashboard/           # Dashboard UI
│   ├── api/                 # Backend APIs
│   │   ├── auth/
│   │   ├── projects/
│   │   └── tasks/
│   └── layout.js
│
├── components/              # UI components
├── lib/                     # Config & utilities
├── models/                  # Mongoose models
├── store/                   # Zustand store
├── styles/                  # Global styles
├── public/                  # Static assets
│
├── .env.local
├── package.json
└── README.md
```

---

## ⚙️ Local Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/team-task-manager.git
cd team-task-manager
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Setup Environment Variables
Create `.env.local` file:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run Development Server
```bash
npm run dev
```

Open 👉 http://localhost:3000

---

## 🚀 Deployment (Railway)

### Step 1: Push Code
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

### Step 2: Deploy
1. Go to https://railway.app  
2. New Project → Deploy from GitHub  
3. Select your repo  
4. Add MongoDB  
5. Add environment variables:
   - `MONGODB_URI`
   - `JWT_SECRET`

Railway will automatically build and deploy your app.

---

