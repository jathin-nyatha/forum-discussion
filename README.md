# 🧵 Forum and Discussion Board Platform

A full-stack discussion board platform where users can create threads, post comments, and engage with a community. Built using the **MERN stack** with JWT-based authentication and RESTful APIs.

---

## 🚀 Features

- ✅ User Registration & Login (JWT)
- 🧵 Create, Edit, Delete Threads
- 💬 Post, Edit, Delete Comments
- 🔒 Secure Route Protection with Middleware
- 🧠 MongoDB Schema Design
- 📱 Responsive UI using React & Tailwind CSS
- ☁️ Deployed on Vercel (Frontend) & Render (Backend)

---

## 🛠️ Tech Stack

| Frontend | Backend          | Database      | Deployment     |
| -------- | ---------------- | ------------- | -------------- |
| React.js | Node.js, Express | MongoDB Atlas | Vercel, Render |

---

## 📁 Project Structure

```
/client       # React app
/server       # Express backend
```

---

## 🧪 API Endpoints

### 👤 Auth

- `POST /api/auth/register`
- `POST /api/auth/login`
- `GET /api/auth/me`

### 🧵 Threads

- `GET /api/threads`
- `POST /api/threads`
- `GET /api/threads/:id`
- `PUT /api/threads/:id`
- `DELETE /api/threads/:id`

### 💬 Comments

- `POST /api/threads/:id/comments`
- `PUT /api/comments/:id`
- `DELETE /api/comments/:id`

---

## 🚦 Getting Started

### 1. Clone Repo

```bash
git clone https://github.com/jathin-nyatha/forum-discussion.git
cd forum
```

### 2. Setup Client

```bash
cd client
npm install
npm start
```

### 3. Setup Server

```bash
cd server
npm install
touch .env   # Add MONGO_URI and JWT_SECRET
npm run dev
```

---

## 📸 Screenshots

![Landing Page](client/public/Landing.png)

---

## 📌 Future Work

- 🔔 Notifications
- 🔎 Search & Filters
- 📅 Google Calendar Integration
- 🏷️ Tag-based Sorting
- 📱 Mobile PWA support

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).  
© 2025 Jathin Nyatha

---

## 🙋‍♂️ Author

## **Jathin Nyatha**
