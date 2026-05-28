# SmartPlacement Portal

A full-stack job placement portal built with React, Node.js, and MongoDB.

🔗 **Live Site:** [Click here]([https://revanthsai09.github.io/portfolio/])

---

## 📁 Project Structure

```
smart-placement-portal/
├── backend/                  ← Node.js + Express API
│   ├── models/               ← Database schemas
│   ├── routes/               ← API endpoints
│   ├── middleware/           ← Auth middleware
│   ├── server.js
│   ├── .env                  ← Your config (edit this!)
│   └── package.json
│
└── frontend/                 ← React app
    └── src/
        ├── pages/            ← Home, Jobs, Dashboard, Admin, Login, Register
        ├── components/       ← Navbar, JobCard
        ├── App.js
        ├── App.css
        ├── api.js
        ├── AuthContext.js
        └── package.json
```

---

## 🛠️ Tech Summary

| Layer      | Technology                          |
|------------|-------------------------------------|
| Frontend   | React.js, React Router, Axios, CSS  |
| Backend    | Node.js, Express.js                 |
| Database   | MongoDB + Mongoose                  |
| Auth       | JWT (JSON Web Tokens) + bcrypt      |
| File Uploads | Multer                            |

---




---

## ✨ Features

- 🔐 User registration & login with JWT auth
- 📋 Browse and apply for job listings
- 🧑‍💼 Admin dashboard to manage jobs and applicants
- 📁 Resume/file upload with Multer
- 📱 Fully responsive design

---

## 📄 License

MIT — free to use and modify.
