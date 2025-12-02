# Copilot Instructions for acme-04-platform Backend (Python)

This is the Python backend repository for acme-04-platform.

## Tech Stack

- FastAPI or Flask
- SQLAlchemy
- pytest
- ruff for linting

## Available Agents

| Agent | Purpose |
|-------|--------|
| `@python` | Endpoint and service development |
| `@api` | API design guidance |

## Commands

```bash
pip install -e .       # Install in dev mode
pytest                 # Run tests
ruff check .           # Lint
ruff format .          # Format
uvicorn main:app       # Run dev server
```

## Project Structure

```
src/
├── api/routes/    # API endpoints
├── core/          # Config, database
├── models/        # SQLAlchemy models
├── schemas/       # Pydantic schemas
└── services/      # Business logic
```
