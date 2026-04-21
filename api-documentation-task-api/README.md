# Task Manager API

This is a REST API for managing tasks.

---

## Base URL
https://api.taskmanager.com

---

## Authentication
Bearer token required in header:

---

## Endpoints

### GET /tasks
Returns all tasks.

**Response:**
```json
[
  {
    "id": 1,
    "title": "Buy groceries",
    "status": "open"
  }
]
