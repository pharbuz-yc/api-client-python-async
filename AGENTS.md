# AGENTS

## Formatting and linting

After each implementation, run these commands:

- .venv/bin/python -m black .
- .venv/bin/ruff check . --fix

If `black` is not available in `.venv`, install it inside that virtual environment (not globally), then run the commands above.