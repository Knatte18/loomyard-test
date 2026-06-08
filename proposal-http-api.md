# HTTP API

A thin HTTP layer over the same storage and validation the CLI uses.

## Endpoints

- `GET /tasks` — list
- `POST /tasks` — upsert
- `POST /tasks/{slug}/phase` — set status
