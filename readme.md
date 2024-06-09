**Run Command**: uvicorn main:app --reload

**Swagger**: url/docs

**DB install**: pip install sqlalchemy alembic psycopg2

**Init Migrations**: alembic init migrations

**Create revision**: alembic revision --autogenerate -m "init"

**Create tables**: alembic upgrade 4203f9b1564d

**Install f-users**: pip install 'fastapi-users[sqlalchemy]'

**Async driver for postgre**: pip install asyncpg



