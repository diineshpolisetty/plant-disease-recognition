# Contributing

Thanks for your interest in contributing to this project! Please follow these steps:

1. Fork the repository and create a feature branch from `main`.
2. Make changes in a topic branch with clear, focused commits.
3. Run formatting and linting locally:

```bash
python -m pip install -r requirements.txt
pip install black ruff
python -m black .
python -m ruff check --fix .
```

4. Open a pull request with a clear description of your changes.
5. Maintain backwards compatibility and include tests where appropriate.
