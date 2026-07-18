# CLAUDE.md

Dockerized ChatGPT command-line client (OpenAI API). Fork / vendored copy of upstream marcolardera/chatgpt-cli; remote `andrius/chatgpt-cli`.

- Base: `python:3-slim`; installs `requirements.txt`, entrypoint `src/chatgpt.py`.
- Config via `config.yaml` (XDG_CONFIG_HOME=/data volume) or `OPENAI_API_KEY` env / `--key` flag.
- Run via `docker-compose.yml` or `docker build`.
- Last commit: 2024-01-22.
