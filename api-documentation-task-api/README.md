# Task Manager System API

This is a REST API for managing tasks in the Task Manager System.

---

## 🌐 Base URL
https://api.taskmanager.com

---

## 🔐 Authentication

All requests require a Bearer token:

Authorization: Bearer <your_token>


---

## 📌 Endpoints

---

### GET /tasks

Returns a list of all tasks.

#### Response
```json
[
  {
    "id": 1,
    "title": "Buy groceries",
    "status": "open"
  }
]
