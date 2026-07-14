<div align="center">

# 💈 Salon Management System

### A full-stack salon operations platform — billing, inventory, staff, and memberships in one place

[![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Vite](https://img.shields.io/badge/Vite-Frontend_Build-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

[![JWT Auth](https://img.shields.io/badge/Auth-JWT_%2B_bcrypt-green?style=flat-square)](#)
[![PDF Reports](https://img.shields.io/badge/Reports-PDF_via_ReportLab-orange?style=flat-square)](#)

</div>

A salon/spa management system covering the day-to-day operations of a multi-branch business: quick-sale billing, service packages, staff assignment across branches, membership plans, and inventory tracking.

## ✨ Features

- 💳 **Quick Sale billing screen** — fast point-of-sale flow for walk-in customers
- 📦 **Package & combo management** — bundle services into packages with configurable pricing
- 👥 **Staff assignment** — assign staff to branches, including temporary cross-branch assignments
- 🎟️ **Membership plans** — recurring membership plans tied to customers
- 📊 **Inventory management** — track product/service stock
- 🧾 **PDF report generation** — billing and business reports via ReportLab
- 🔐 **JWT authentication** — bcrypt-hashed credentials, role-based access (manager passwords, etc.)
- ☁️ **MongoDB Atlas backed** — migrated from a relational schema to a document store

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Flask, MongoEngine, PyMongo |
| Frontend | React 18, Vite, Ant Design, Zustand |
| Database | MongoDB |
| Auth | JWT, bcrypt |
| Reports | ReportLab (PDF), xlsx (Excel export) |
| Charts | Recharts |
| Deployment | Docker, Cloud Run |

## 🚀 Getting Started

### Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## 📬 Contact

- **Email:** arunkishore757@gmail.com
- **GitHub:** [@Kishore-official](https://github.com/Kishore-official)
