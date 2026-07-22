<div align="center">

# 🚀 CORE.MATRIX

### Modern Full-Stack Habit Tracking Platform

**Build Discipline • Track Progress • Visualize Consistency**

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot)
![Gradle](https://img.shields.io/badge/Gradle-8.x-02303A?style=for-the-badge&logo=gradle)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=for-the-badge&logo=postgresql)
![JWT](https://img.shields.io/badge/JWT-Secure-black?style=for-the-badge)
![Render](https://img.shields.io/badge/Render-Cloud-46E3B7?style=for-the-badge&logo=render)
![Vercel](https://img.shields.io/badge/Vercel-Frontend-black?style=for-the-badge&logo=vercel)

A production-ready Full-Stack Habit Tracking application built using **Spring Boot**, **React**, **TypeScript**, and **Neon PostgreSQL**.

</div>

---

# 🌐 Live Demo

### 🎨 Frontend

https://core-tracker-ui.vercel.app/

### ⚙️ Backend API

https://core-tracker-api-tyf8.onrender.com

---

# 📦 Source Code

## 🎨 Frontend Repository

https://github.com/Narra-Uttam-Kumar/core-tracker-ui

## ⚙️ Backend Repository

https://github.com/Narra-Uttam-Kumar/core-tracker-api

---

# ✨ Features

- 🔐 Secure User Authentication
- 🔑 JWT Authentication
- 🛡 Spring Security
- 🔒 BCrypt Password Encryption
- 📅 Daily Habit Tracking
- 📆 Monthly Habit Matrix
- 📊 Analytics Dashboard
- 📈 Detailed Habit Statistics
- 🎯 Habit Goal Management
- 📱 Responsive Design
- ☁️ Cloud Deployment
- ⚡ RESTful APIs
- 🗄 PostgreSQL Persistence

---

# 📸 Screenshots

| Login | Register |
|-------|----------|
| ![](screenshots/login.png) | ![](screenshots/register.png) |

| Habit Matrix | Analytics Dashboard |
|--------------|---------------------|
| ![](screenshots/sheet.png) | ![](screenshots/analytics.png) |

| Detailed Analytics | Year Overview |
|--------------------|---------------|
| ![](screenshots/detailed.png) | ![](screenshots/year.png) |

| Habit Details |
|---------------|
| ![](screenshots/habit.png) |

---

# 🏗️ System Architecture

```text
                 React + TypeScript (Vite)
                          │
                     HTTPS REST API
                          │
                          ▼
                Spring Boot Backend
                          │
          Spring Security + JWT Authentication
                          │
                    Service Layer
                          │
               Spring Data JPA + Hibernate
                          │
                          ▼
               Neon PostgreSQL Database
```

---

# 🛠 Technology Stack

| Category | Technologies |
|-----------|--------------|
| Language | Java 21, TypeScript |
| Frontend | React 18, Vite |
| Backend | Spring Boot 3 |
| Security | Spring Security, JWT, BCrypt |
| ORM | Spring Data JPA, Hibernate |
| Database | PostgreSQL (Neon) |
| Build Tool | Gradle |
| Deployment | Vercel, Render, Neon |

---

# 📂 Project Structure

```text
CORE-TRACKER

├── frontend
│   ├── src
│   ├── components
│   ├── hooks
│   ├── utils
│   └── assets
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── security
│   ├── model
│   ├── dto
│   └── config
│
├── screenshots
│   ├── login.png
│   ├── register.png
│   ├── sheet.png
│   ├── analytics.png
│   ├── detailed.png
│   ├── year.png
│   └── habit.png
│
└── README.md
```

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

# 🔐 Security

- JWT Authentication
- Spring Security
- BCrypt Password Encryption
- Stateless Authentication
- CORS Configuration
- Protected REST APIs

---

# ☁️ Deployment

| Component | Platform |
|-----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | Neon PostgreSQL |

---

# ⚙️ Local Installation

## Clone the repositories

```bash
git clone https://github.com/Narra-Uttam-Kumar/core-tracker-api.git

git clone https://github.com/Narra-Uttam-Kumar/core-tracker-ui.git
```

---

## Backend

```bash
cd core-tracker-api

./gradlew build

./gradlew bootRun
```

For Windows:

```bash
gradlew.bat build

gradlew.bat bootRun
```

---

## Frontend

```bash
cd core-tracker-ui

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
JWT_SECRET=<your-secret>
ALLOWED_ORIGINS=https://core-tracker-ui.vercel.app
```

## Frontend

```env
VITE_API_BASE_URL=https://core-tracker-api-tyf8.onrender.com/api
```

---

# 🚀 Future Enhancements

- 🤖 AI Habit Recommendations
- 📱 Mobile Application
- 🏆 Habit Streak Rewards
- 📧 Email Notifications
- 📊 Advanced Analytics
- 📤 CSV / Excel Export
- 🌙 Dark & Light Themes
- 🔔 Push Notifications

---

# 💼 Skills Demonstrated

- Full Stack Development
- Enterprise Java Development
- Spring Boot REST APIs
- Spring Security & JWT
- React + TypeScript
- PostgreSQL Database Design
- Hibernate ORM
- Cloud Deployment
- Clean Architecture
- Production-Ready Development

---

# 👨‍💻 Author

## Uttam Kumar Reddy

**Java Full Stack Developer**

### Technologies

Java • Spring Boot • Spring Security • Gradle • React • TypeScript • PostgreSQL • Hibernate • REST APIs • JWT

---

<div align="center">

## ⭐ If you like this project, please give it a Star!

Built with ❤️ using Spring Boot, React, Gradle, Render, Vercel & Neon PostgreSQL.

</div>
