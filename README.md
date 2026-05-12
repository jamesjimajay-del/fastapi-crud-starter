# 🚀 FastAPI CRUD Starter

A **production-ready** FastAPI starter template with SQLAlchemy, Alembic, Pydantic v2, JWT authentication, and Docker support.

## Features
- ✅ Full CRUD for Items
- 🔐 JWT Authentication
- 📁 Alembic migrations
- 🛢️ Docker + docker-compose
- 🔄 Async support
- 📊 OpenAPI docs at /docs

## Quick Start

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run migrations
alembic upgrade head

# 3. Start server
uvicorn main:app --reload
```

Then visit http://localhost:8000/docs

## Tech Stack
- FastAPI + Pydantic v2
- SQLAlchemy 2.0 + Alembic
- PostgreSQL (or SQLite for dev)
- JWT + Passlib
- Docker

Made with ❤️ by jamesjimajay-del