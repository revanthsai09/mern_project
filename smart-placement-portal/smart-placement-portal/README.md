# SmartPlacement Portal — 


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

Tech Summary :

- **Frontend**: React.js, React Router, Axios, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB + Mongoose
- **Auth**: JWT (JSON Web Tokens) + bcrypt password hashing
- **File uploads**: Multer
