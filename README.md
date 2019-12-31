# ds-study

study data science.

## Requirements

- poetry>=0.12

## Instalation

```bash
# create venv directory in this project to inform package information to IDE.
# if using VSCode, don't forget to set Python:Venv Path in Settings.
poetry config virtualenvs.in-project true

# install
poetry install
```

## Run

```bash
poetry run python main.py
```

## TypeCheck
Config file is `mypy.ini`.
```bash
poetry run mypy .
```

## Lint
Config file is `.flake8`.
```bash
poetry run flake8 .
```

## Format
No config flie but uses flake8 inside it.
```bash
poetry run black .
```
