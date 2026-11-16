# Day 1 DevOps Workshop Starter


```bash
python -m venv .venv
# Linux/macOS: source .venv/bin/activate
# Windows PowerShell: .venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m uvicorn app.main:app --reload
```

Open http://127.0.0.1:8000/docs (Swagger UI) and /health.

Tests: `python -m pytest -q`

Lint: `ruff check .`

Hello world