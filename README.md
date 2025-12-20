# 📝 ToDoList – Full Stack Application (React + Spring Boot)

A simple yet powerful **full-stack ToDo List application** built using **React.js (Vite)** for the frontend and **Spring Boot** for the backend.
This project demonstrates clean separation of concerns, RESTful APIs, and real-world full-stack development practices.

---

## 🚀 Tech Stack

### Frontend

* ⚛️ React.js (Vite)
* 🎨 CSS
* 📦 npm
* 🌐 Axios (for API calls)

### Backend

* ☕ Java
* 🌱 Spring Boot
* 🔗 REST APIs
* 📦 Maven

---

## 📂 Project Structure

```
ToDoList/
│
├── backend/
│   └── todolistbackend/
│       ├── src/main/java
│       ├── src/main/resources
│       ├── pom.xml
│       └── mvnw
│
├── frontend/
│   └── ToDoListFrontend/
│       ├── src/
│       ├── public/
│       ├── package.json
│       └── vite.config.js
│
└── README.md
```

---

## ✨ Features

* ➕ Add new tasks
* 📋 View all tasks
* ❌ Delete tasks
* 🔄 Real-time UI updates
* 🌐 REST API integration between frontend and backend
* 🧩 Clean and modular codebase

---

## 🛠️ Getting Started

### Prerequisites

Make sure you have these installed:

* Node.js (v18+ recommended)
* Java JDK 17+
* Maven
* Git

---

## ▶️ Run Backend (Spring Boot)

```bash
cd backend/todolistbackend
./mvnw spring-boot:run
```

Backend will start on:

```
http://localhost:8080
```

---

## ▶️ Run Frontend (React)

```bash
cd frontend/ToDoListFrontend
npm install
npm run dev
```

Frontend will start on:

```
http://localhost:5173
```

---

## 🔗 API Overview

| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | `/todos`      | Fetch all todos   |
| POST   | `/todos`      | Create a new todo |
| DELETE | `/todos/{id}` | Delete a todo     |

*(Endpoints may vary based on implementation)*

---
## 🎯 Future Improvements

* ✏️ Edit todo items
* 🔐 Authentication & Authorization
* 🗄️ Database integration (MySQL/PostgreSQL)
* 📱 Responsive UI improvements
* 🧪 Unit & integration tests

---

## 👨‍💻 Author

**Harshit Kushwaha**

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub — it really helps!
