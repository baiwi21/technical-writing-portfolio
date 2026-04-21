# Task Manager System API

This is a REST API for managing tasks in the Task Manager System.

---

## 🌐 Base URL
https://api.taskmanager.com

---

## 🔐 Authentication

All requests require a Bearer token:

```
Authorization: Bearer <your_token>
```

---

## 📌 Endpoints

---

### ➕ Create a task

**POST** `/tasks`

Creates a new task.

#### Request Body
```json
{
  "title": "New task"
}
```

#### Response
```json
{
  "id": 2,
  "title": "New task",
  "status": "open"
}
```

---

### 📄 Get all tasks

**GET** `/tasks`

#### Response
```json
[
  {
    "id": 1,
    "title": "Buy groceries",
    "status": "open"
  },
  {
    "id": 2,
    "title": "New task",
    "status": "open"
  }
]
```

---

### 🗑️ Delete a task

**DELETE** `/tasks/{id}`

#### Response
```json
{
  "message": "Task deleted successfully"
}
```
