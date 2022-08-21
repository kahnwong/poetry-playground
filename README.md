# poetry-playground

## Setup

```bash
brew install poetry
```

## Usage

```bash
pyenv local 3.9.11
poetry init
poetry install --no-dev

# cookie cutter project template
poetry new --src my-package
```

### Remove env

```bash
poetry env list
poetry env remove ${ENV_NAME}
```
