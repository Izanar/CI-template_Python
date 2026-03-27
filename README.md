# Template API

## Setup:
```bash
uv sync
```

### Start with uv
```bash
uv run app
```

### Start with docker
```bash
docker compose up --build -d
```

## Pre-commit hooks

Install and setup pre-commit hooks:
```bash
uv sync --group dev
pre-commit install
```

Run hooks manually:
```bash
pre-commit run --all-files
```

## CLI:

### Create migration
```bash
uv run cli migration
```

### Upgrade database with alembic
```bash
uv run cli upgrade
```

## Monitoring

- **Grafana**: http://localhost:3000 (admin/admin)
- **Prometheus**: http://localhost:9090
- **Loki**: http://localhost:3100

[![pipeline status](https://gitlab.com/Izanar/CI-template/badges/main/pipeline.svg)](https://gitlab.com/Izanar/CI-template/-/commits/main)
