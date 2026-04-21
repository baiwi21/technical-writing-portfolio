# Task Manager API Documentation

## Overview
This API allows managing tasks in the system.

---

## Base URL
https://api.example.com

---

## Endpoints

### GET /tasks
Returns all tasks.

Response:
```json
[
  {
    "id": 1,
    "title": "Buy groceries",
    "status": "open"
  }
]
