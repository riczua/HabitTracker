# HabitTracker

Habit tracking REST API with daily check-ins and streak statistics.

Built with FastAPI + SQLAlchemy, tested with pytest, as a portfolio project
demonstrating Python backend development and API test automation.

## Status

🚧 Work in progress.

## Tech stack

- FastAPI (REST API)
- SQLAlchemy + SQLite (persistence)
- Pydantic (validation / DTOs)
- pytest + httpx (unit + API tests)
- ruff + mypy (linting / type checking)

## Running locally

```bash
uv sync
uv run uvicorn habittracker.api.api:app --reload
```

## Running tests

```bash
uv run pytest
```
