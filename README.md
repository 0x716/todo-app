# 📝 Todo App – Fullstack Monorepo (Go + React + PostgreSQL)

This is a fullstack TODO application built using:

- **Go (Gin)** as the backend RESTful API framework
- **React + Vite + TypeScript** for the frontend SPA
- **PostgreSQL** as the database
- **Docker & Docker Compose** for development and deployment

Everything is organized under a monorepo structure to make development and deployment easier.

---

## 📦 Tech Stack

| Layer      | Technology                 |
|------------|----------------------------|
| Backend    | Go + Gin, PostgreSQL       |
| Frontend   | React, Vite, TypeScript    |
| Config     | Viper + YAML               |
| Deployment | Docker, Docker Compose     |

---

## 📁 Project Structure
```
todo-app/
├── backend/ # Go API using Gin
├── frontend/ # React SPA (Vite + TypeScript)
├── docker/ # Docker Compose & Nginx config
└── README.md
```
---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourname/todo-app.git
cd todo-app

