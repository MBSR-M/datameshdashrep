| Category                | Packages                                                              | Purpose                                         |
| ----------------------- | --------------------------------------------------------------------- | ----------------------------------------------- |
| **FastAPI Stack**       | `fastapi`, `uvicorn`, `gunicorn`                                      | Web app framework, ASGI server, WSGI server     |
| **Kafka**               | `kafka-python`, `confluent-kafka`                                     | Kafka client options (choose based on use case) |
| **Redis**               | `redis`                                                               | Redis support                                   |
| **SQL DB**              | `sqlalchemy`, `psycopg2-binary`, `asyncpg`                            | ORM & PostgreSQL drivers (sync + async)         |
| **MongoDB**             | `pymongo`, `motor`                                                    | Sync + Async MongoDB clients                    |
| **Data Tools**          | `pandas`, `numpy`, `python-dateutil`, `tzlocal`                       | Data processing & time zone utilities           |
| **Config & Secrets**    | `python-dotenv`, `pyyaml`, `cryptography`                             | Manage env/config/secrets                       |
| **Auth/Security**       | `passlib[bcrypt]`, `python-jose[cryptography]`, `jwt`, `itsdangerous` | Password hashing, token-based auth, JWTs        |
| **Validation & Models** | `pydantic[dotenv,email]`                                              | Robust validation, email and dotenv support     |
| **API Clients**         | `httpx`, `aiohttp`                                                    | HTTP clients (sync and async)                   |
| **Auth Management**     | `fastapi-users`                                                       | User registration, login, password reset, etc.  |
| **Task Queue**          | `celery`                                                              | Background jobs, scheduling                     |
| **CLI Tooling**         | `typer`                                                               | CLI support                                     |
| **Logging**             | `loguru`                                                              | Advanced logging                                |
| **Migrations**          | `alembic`                                                             | DB schema migration for SQLAlchemy              |
