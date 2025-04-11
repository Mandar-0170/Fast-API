# FastAPI Docker App – User Management Microservice

A containerized FastAPI application that supports user creation and listing, with data persisted to a JSON file for lightweight storage. Fully deployable via Docker Compose.

---

# Features

- Docker + Docker Compose support
- User data saved to `users.json` in a volume-mapped folder
- Stateless containers with persistent user data

---

# Tech Stack

- Python 3.10+
- FastAPI 0.92
- Uvicorn
- Docker & Docker Compose
- JSON file (instead of DB)


