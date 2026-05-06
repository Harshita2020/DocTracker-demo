# 📋 Student Document Tracker (MERN)

A full-stack MERN application built to streamline tracking and verification of student admission documents. Designed with a responsive interface and persistent storage for efficient real-world usage.

---

## 🚀 Live Demo

- Frontend (Netlify): <your-netlify-url>
- Backend (Render): <your-render-url>

---

## ✨ Features

- 📊 Track document submission status per student
- 💾 Persistent storage using MongoDB Atlas
- 📱 Responsive and mobile-friendly UI
- 📄 Export reports as:
  - PDF
  - Excel
  - JSON backup
- 🔄 Real-time document status updates
- 📈 Summary dashboard with completion insights

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- JavaScript (ES6+)
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas

### Deployment
- Netlify
- Render

---

## 📁 Project Structure

```txt
doc-tracker/
│
├── client/         # React frontend
├── server/         # Express backend
└── README.md
```

---

## ⚙️ Environment Variables

### Frontend (`client/.env`)
```env
VITE_BASE_URL=https://your-backend-url
```

### Backend (`server/.env`)
```env
MONGO_URL=your_mongodb_connection_string
PORT=5000
```

---

## 🧪 Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/Harshita2020/DocTracker-demo
cd student-document-tracker
```

### 2. Start Backend

```bash
cd server
npm install
npm run dev
```

### 3. Start Frontend

```bash
cd client
npm install
npm run dev
```

---

## 📌 Key Learnings

- Building and deploying a full-stack MERN application
- Managing frontend-backend API integration
- Handling MongoDB Atlas connections and environment variables
- Debugging deployment workflows across Netlify and Render
- Designing solutions for real-world operational workflows

---

## 🔮 Future Improvements

- Authentication & role-based access
- Add/Edit student management
- Multi-class support
- Enhanced analytics dashboard
- Progressive Web App (PWA) support

---

## 👩‍💻 Author

Harshita A