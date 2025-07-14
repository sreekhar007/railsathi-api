# 🚆 Rail Sathi API

A FastAPI-based backend service for managing railway complaints efficiently. The system enables users to submit, retrieve, and manage complaints, offering a clean REST API and database support using PostgreSQL. Built for scalability, maintainability, and easy containerized deployment.

---

## 📦 Tech Stack

- **FastAPI** – Lightning-fast ASGI web framework
- **PostgreSQL** – Reliable and powerful relational database
- **Docker & Docker Compose** – Containerized development and deployment
- **Pydantic** – Data validation and settings management
- **Uvicorn** – ASGI server for FastAPI
- **psycopg2** – PostgreSQL database adapter for Python

---

##  Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/sreekhar007/railsathi-api
cd railsathi-api
cp .env.example .env
docker-compose up --build
http://localhost:8000/items/

