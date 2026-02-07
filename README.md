# FullStack Store Rating Application

This project is a FullStack web application built with:

- **Frontend:** React.js (Vite)
- **Backend:** Node.js + Express
- **Database:** MySQL (XAMPP)

---

## 📁 Project Structure

```
root
│
├── client/                 # React Frontend
│   ├── public/
│   │   └── index.html
│   │
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Login.jsx
│   │   │   ├── Signup.jsx
│   │   │   ├── AdminDashboard.jsx
│   │   │   ├── StoreOwnerDashboard.jsx
│   │   │   ├── UserHomePage.jsx
│   │   │   ├── AllStoresPages.jsx
│   │   │   ├── UserRatingsPage.jsx
│   │   │   ├── UpdatePassword.jsx
│   │   │   ├── UserList.jsx
│   │   │   ├── RateStorePage.jsx
│   │   │   ├── StoreList.jsx
│   │   │   ├── AddUserPage.jsx
│   │   │   └── AddStorePage.jsx
│   │   │
│   │   ├── services/
│   │   │   ├── authService.jsx
│   │   │   ├── userService.jsx
│   │   │   ├── storeService.jsx
│   │   │   └── ratingService.jsx
│   │   │
│   │   ├── App.jsx
│   │   └── index.jsx
│   │
│   ├── vite.config.js
│   └── package.json
│
├── server/                 # Node.js + Express Backend
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── userController.js
│   │   ├── storeController.js
│   │   ├── ratingController.js
│   │   └── adminController.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── userRoutes.js
│   │   ├── storeRoutes.js
│   │   ├── ratingRoutes.js
│   │   └── adminRoutes.js
│   │
│   ├── middleware/
│   │   └── authMiddleware.js
│   │
│   ├── config/
│   │   └── db.js
│   │
│   ├── models/
│   │   ├── User.js
│   │   ├── Store.js
│   │   └── Rating.js
│   │
│   ├── .env
│   ├── app.js
│   └── package.json
│
└── database/               # MySQL (XAMPP)
```

---

## 🚀 Features

- JWT Authentication
- Role-based Access Control (Admin / Store Owner / User)
- Store Rating System
- Dashboard Views
- Secure Password Handling

---

## ⚙️ Installation

### Backend Setup

```bash
cd server
npm install
npm start
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## 🛢 Database Setup

1. Start XAMPP
2. Start MySQL
3. Create database
4. Import schema

---

## 👩‍💻 Author

Sakshi Kuyte  
GitHub: https://github.com/kuytesakshi
