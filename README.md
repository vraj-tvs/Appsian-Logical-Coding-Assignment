# Full Stack Development Assignments — Problem Statement

This repository contains the **official problem statement** for two structured web development assignments designed to evaluate end-to-end proficiency in **C# (.NET 8)** and **React with TypeScript**.

Each assignment focuses on both **frontend** and **backend** development and is meant to simulate real-world development tasks involving REST APIs, user authentication, and UI state management.

---

## 📄 Problem Statement Overview

### 🧩 Home Assignment 1 – Basic Task Manager

**Objective:**  
Develop a simple full-stack web application that allows users to manage tasks with complete CRUD functionality.

**Core Requirements:**

- Display and manage a list of tasks
- Add, toggle (complete/incomplete), and delete tasks
- Use **React (TypeScript)** for frontend
- Implement **REST API** using **.NET 8 Core**
- Use **in-memory storage**

**Enhancements (Optional):**

- Task filters (All / Completed / Active)
- Responsive UI using Bootstrap or Tailwind
- Persist tasks in `localStorage`

**Solution Repository:**  
🔗 [Task Manager](https://github.com/vraj-tvs/Task_Manager)

---

### 💼 Home Assignment 2 – Mini Project Manager

**Objective:**  
Build a **modular, full-stack project management system** with authentication, multi-entity relationships, and a responsive frontend.

**Business Context:**  
Users can register, log in, create multiple projects, and manage tasks within each project.

**Core Features:**

- **Authentication:** JWT-based registration & login
- **Projects:** CRUD operations with ownership restrictions
- **Tasks:** Manage tasks linked to projects
- **Frontend:** SPA built using React with routing & state management

**Backend Requirements:**

- REST API using **.NET 8 Core** + **Entity Framework Core**
- Use **SQLite** or in-memory database
- Implement structured architecture (DTOs, services, models)

**Frontend Requirements:**

- Built with **React + TypeScript**
- Pages: Login, Register, Dashboard, Project Details
- Form validation and API integration via Axios
- Store JWT for authenticated requests
- Navigation using **React Router**

**Enhancements:**

- Smart Scheduler API (`POST /api/v1/projects/{projectId}/schedule`)
- Loading indicators and animations
- Mobile-friendly, responsive design
- Deployed frontend on **Vercel**, backend on **Render**

**Solution Repositories:**  
🔗 Frontend: [Mini Project Manager - Frontend](https://github.com/vraj-tvs/Mini-Project-Manager-Frontend)  
🔗 Backend: [Mini Project Manager - Backend](https://github.com/vraj-tvs/Mini-Project-Manager-Backend)

---

## 🧱 Deliverables and Structure

Each project includes:

- Well-documented codebases with clear structure
- RESTful APIs following clean architecture principles
- Fully functional UI with integrated backend APIs
- JWT-secured endpoints and protected frontend routes

---

## 📦 Problem Statement Document

Download or view the detailed **problem statement** here:  
📄 [Problem_Statement.pdf](./Problem_Statement.pdf)
