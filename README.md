# 🚀 Team Task Manager (Full-Stack)

A full-stack web application to manage team projects, assign tasks, and track progress with role-based access (Admin & Member).

---

## 🌐 Live Application

🔗 Frontend: https://team-work-manager.netlify.app/
🔗 Backend: https://team-task-manager-production-1f78.up.railway.app/

🔗 Live Link: https://team-work-manager.netlify.app/


---

## 🎥 Demo Video

🔗 https://drive.google.com/file/d/1e6I1fg6O5m79KzycXJ-J6Hf74BDo7q6i/view?usp=sharing

---

## ✨ Key Features

### 🔐 Authentication

* Secure Signup & Login using JWT
* Protected routes with middleware

### 👥 Role-Based Access Control

* **Admin**

  * Create projects
  * Assign tasks to team members
  * View all created tasks
* **Member**

  * View assigned tasks only
  * Update task status

### 📁 Project Management

* Admin can create projects
* Tasks are linked with specific projects

### ✅ Task Management

* Create tasks with:

  * Title
  * Description
  * Assigned user
  * Project
  * Due date
* Status tracking:

  * Todo
  * In Progress
  * Completed

### 📊 Dashboard

* View total tasks
* Track in-progress and completed tasks
* Real-time updates (auto refresh)

---

## 🛠 Tech Stack

### Frontend

* React (Vite)
* Axios
* Custom CSS (Responsive UI)

### Backend

* Node.js
* Express.js
* REST API

### Database

* MongoDB (Mongoose)

### Deployment

* Frontend → Netlify
* Backend → Railway

---

## ⚙️ Project Structure

```
team-task-manager/
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
├── frontend/
│   ├── src/
│   └── public/
│
└── README.md
```

---

## 🔒 Role Logic

* Admin can manage all tasks they create
* Members can only access tasks assigned to them
* Authorization handled securely on backend

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AdiCoder0721/team-task-manager.git
cd team-task-manager
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create `.env` file inside backend:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## 📸 Screenshots (Optional but Recommended)


<img width="1919" height="926" alt="Screenshot 2026-05-01 121043" src="https://github.com/user-attachments/assets/88e2b33d-aba8-49f0-a94f-00fa656d899e" />

* <img width="1919" height="924" alt="Screenshot 2026-05-01 121031" src="https://github.com/user-attachments/assets/c639c636-9c79-42c5-81cf-287d2f3298af" />


* <img width="1919" height="930" alt="Screenshot 2026-05-01 121003" src="https://github.com/user-attachments/assets/012951f7-6449-4b4a-be71-7d9130bb4617" />


---

## 📈 Future Improvements

* Real-time updates using WebSockets
* Task notifications
* File attachments
* Kanban board view

---

## 👨‍💻 Author

**Aditya Yadav**
GitHub: https://github.com/AdiCoder0721/team-task-manager

---

## ⭐ Final Note

This project was built as part of a technical assessment to demonstrate full-stack development skills, REST API design, authentication, and role-based systems.
