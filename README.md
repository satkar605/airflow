# Airflow

Exploring the latest architecture of Airflow 3.0

*In line with the new Manning book*

## Quick start

1. Set `AIRFLOW_UID` in `.env` (e.g. `50000`).
2. Run `docker compose up -d`.
3. Open the UI at http://localhost:8080 (default: airflow / airflow).

## Repo layout

- `dags/` – DAG definitions
- `config/` – Airflow config
- `docker-compose.yaml` – Stack (Postgres, Redis, scheduler, workers, API)

Co-authored with Mohit Acharya.