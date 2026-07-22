
# 🚀 CORE.MATRIX

<div align="center">

### Modern Full-Stack Habit Tracking Platform

**Build Discipline • Track Progress • Visualize Consistency**

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=for-the-badge&logo=postgresql)
![JWT](https://img.shields.io/badge/JWT-Authentication-black?style=for-the-badge)

A production-ready full-stack Habit Tracking application built with **Spring Boot**, **React**, **TypeScript**, and **Neon PostgreSQL**.

</div>

---

# ✨ Features

- 🔐 JWT Authentication
- 🛡️ Spring Security
- 🔒 BCrypt Password Encryption
- 📅 Daily Habit Tracking
- 📆 Monthly Habit Matrix
- 📊 Analytics Dashboard
- 📈 Detailed Statistics
- 🎯 Habit Goal Management
- 📱 Responsive UI
- ☁️ Cloud Deployment

---

# 🔗 Project Links

## 🎨 Frontend Repository
> Replace with your repository URL

`https://github.com/Narra-Uttam-Kumar/core-tracker-ui`

## ⚙️ Backend Repository
> Replace with your repository URL

`https://github.com/Narra-Uttam-Kumar/core-tracker-api`

## 🌐 Live Frontend (Vercel)

`https://core-tracker-ui.vercel.app/`

## 🚀 Backend API (Render)

`https://core-tracker-api-tyf8.onrender.com`

## 🗄️ Database

- Neon PostgreSQL (Serverless)

---

# 🏗️ Architecture

```text
React + TypeScript (Vite)
          │
          ▼
 REST API (HTTPS)
          │
          ▼
 Spring Boot Backend
          │
 Spring Security + JWT
          │
          ▼
 Spring Data JPA
          │
          ▼
 Neon PostgreSQL
```

---

# 🛠️ Technology Stack

| Layer | Technology |
|------|------------|
| Frontend | React 18, TypeScript, Vite |
| Backend | Java 21, Spring Boot 3 |
| Security | Spring Security, JWT, BCrypt |
| Database | PostgreSQL (Neon) |
| ORM | Hibernate, Spring Data JPA |
| Deployment | Vercel, Render, Neon |

---

# 📂 Project Structure

```text
core-matrix/
├── frontend/
│   ├── components/
│   ├── hooks/
│   ├── utils/
│   └── assets/
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── security/
│   ├── model/
│   └── config/
├── screenshots/
└── README.md
```

---

# 📸 Screenshots

Place your screenshots in a `screenshots` folder.

- login.png
- register.png
- sheet.png
- monthly.png
- analytics.png
- detailed.png
- year.png
- habit.png

---

# 📡 REST APIs

## Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

## Habits

```http
GET    /api/habits
POST   /api/habits/toggle
PUT    /api/habits/goals
GET    /api/habits/analytics
```

---

# ⚙️ Installation

## Backend

```bash
mvn clean install
mvn spring-boot:run
```

## Frontend

```bash
npm install
npm run dev
```

---

# 🌍 Environment Variables

## Backend

```env
DB_URL=jdbc:postgresql://<host>/<database>?sslmode=require
DB_USERNAME=<username>
DB_PASSWORD=<password>
JWT_SECRET=<secret>
ALLOWED_ORIGINS=<frontend-url>
```

## Frontend

```env
VITE_API_BASE_URL=https://core-tracker-api-tyf8.onrender.com/api
```

---

# ☁️ Deployment

| Component | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | Neon PostgreSQL |

---

# 🚀 Future Enhancements

- AI Habit Recommendations
- Email Notifications
- Mobile Application
- Habit Streak Rewards
- Export Reports
- Dark/Light Themes

---

# 👨‍💻 Author

**Uttam Kumar Reddy**

Java Full Stack Developer

**Skills:** Java • Spring Boot • React • TypeScript • PostgreSQL • REST APIs • JWT • Spring Security

---

<div align="center">

### ⭐ If you like this project, please give it a Star!

Built with ❤️ using Spring Boot, React, Render, Vercel & Neon PostgreSQL.

</div>
