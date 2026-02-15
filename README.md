# Task 02: Persistent Storage with Database Integration

A FastAPI application integrated with **PostgreSQL** for persistent data storage, featuring SQLAlchemy ORM and Alembic migrations.

## 🗄️ Architecture
* **FastAPI:** Handles HTTP requests and routing.
* **SQLAlchemy:** Translates Python classes to SQL tables.
* **PostgreSQL:** Stores the user data reliably.
* **Alembic:** Manages database schema changes over time.

## ⚙️ Environment Setup
1. Create a `.env` file:
   ```ini
   DATABASE_URL=postgresql://user:pass@localhost/dbname

---
# Author
- Name: Pruonh Kimliya
- Email: kimliyapruonh@gmail.com
