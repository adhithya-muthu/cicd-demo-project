# CI/CD Pipeline Demo

A basic CI/CD pipeline demo using GitHub Actions.

## Pipeline Stages

| Stage | Description |
|---|---|
| Trigger | Push or PR to `main` branch |
| Install | Install Python dependencies |
| Test | Run pytest test cases |
| Deploy | Simulated deploy (only on `main`) |

## Run Locally

```bash
pip install -r requirements.txt
pytest test_app.py
```
