# Run the FastAPI project

This project is a FastAPI app for a task management API. It is intentionally unfinished in a few places, but the app itself can still start locally.

## 1) Open the project folder

```bash
cd c:/Users/chennakesava/Desktop/lab8/week2/copilot_demo_unfinished_project
```

## 2) Create and activate a virtual environment

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

## 3) Install dependencies

```bash
pip install -r requirements.txt
```

## 4) Start the app

```bash
uvicorn app.main:app --reload
```

The server should start on:

```text
http://127.0.0.1:8000
```

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

## 5) Check the app is running

Open the health endpoint:

```text
http://127.0.0.1:8000/health
```

Expected response:

```json
{"status": "ok"}
```

## 6) Run the tests

```bash
pytest -q
```

Note: this project includes intentionally unfinished deletion behavior, so the full suite may fail until that TODO is implemented.

## Useful commands

```bash
# stop the running server
Ctrl + C

# activate the environment again later
.\.venv\Scripts\Activate.ps1
```

## Project notes

- App entry point: `app/main.py`
- API routes: `app/api/routes.py`
- Service layer: `app/services/task_service.py`
- Repository layer: `app/repositories/task_repository.py`
