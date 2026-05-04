# 🧩 DevConnect API — Learn Backend by Building a Real System

> A beginner-friendly backend project where contributors build a real-world API step by step using FastAPI.

---

## 🎯 What is this project?

**DevConnect API** is a simplified backend system that simulates a developer social platform.

It allows users to:

* Create profiles
* Share data (posts in future)
* Interact via APIs

This project is not just about code — it's about learning how real backend systems are structured.

---

## 🧠 Why this project exists

Most beginners:

* watch tutorials
* build isolated mini-projects
* don’t understand real backend architecture

This project solves that by:

* breaking a real system into small tasks
* allowing contributors to implement features incrementally

---

## ⚠️ What You Will ACTUALLY Do in This Project

This section is critical.

You are not just "reading code" — you will **build parts of the backend step by step**.

### You will work like this:

1. Pick a small task (issue)
2. Implement that feature in code
3. Submit a Pull Request
4. Get feedback and improve

---

## 🧩 Step-by-Step What You Will Build

You will gradually build a complete backend system.

### Phase 1 — Basic Setup

* Create FastAPI app
* Run server locally
* Understand project structure

### Phase 2 — First API

* Create `/health` endpoint
* Return simple JSON response

### Phase 3 — Database Integration

* Define **User model**
* Connect to database

### Phase 4 — CRUD APIs

* Create user (POST `/users`)
* Get users (GET `/users`)

### Phase 5 — Expand Features (later)

* Update user
* Delete user
* Add posts system

---

## 🔍 Example: What a Task Looks Like

### Issue Example:

**Title:** Add `/health` endpoint

### Your job:

* Go to `routes/`
* Create a new route file or update existing one
* Add:

```python
@router.get("/health")
def health_check():
    return {"status": "ok"}
```

### After that:

* Run the server
* Test endpoint in browser or Postman
* Submit PR

👉 This is how every task works.

---

## ⚙️ Tech Stack

* FastAPI
* MySQL
* SQLAlchemy
* Pydantic

---

## 🏗️ What You Will Learn

* API development (REST)
* Database design
* Backend architecture (routes, services, models)
* GitHub workflow (issues → PR → review)

---

## 🚀 Current Features (Incremental)

* [ ] Project setup
* [ ] Health check endpoint
* [ ] User model
* [ ] Create user API
* [ ] Get users API

---

## 📂 Project Structure

```bash
app/
 ├── main.py
 ├── routes/
 ├── models/
 ├── schemas/
 ├── database/
 └── services/
```

---

## ⚡ How to Run Locally

```bash
git clone <repo-url>
cd devconnect-api

pip install -r requirements.txt

uvicorn app.main:app --reload
```

---

## 🤝 How to Contribute

1. Go to Issues
2. Pick a `good-first-issue`
3. Comment to get assigned
4. Submit PR

---

## 📌 Important

* You don’t need to know everything before starting
* Tasks are intentionally small
* You will learn by doing, not by watching
* Mistakes are expected and part of learning

---

## 🧭 Where to Start?

👉 Go to **Issues Tab**
👉 Pick your first task
👉 Start building

---

## 👨‍💻 Maintained By

Pandva Open Dev Community
