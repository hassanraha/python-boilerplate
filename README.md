# My Project

This is a boilerplate Python project using Poetry, pre-commit, and GitHub Actions.

## Setup

1. Make sure you have Python 3.12 installed.
2. Install Poetry: https://python-poetry.org/docs/#installation
3. Clone this repository.
4. Run `poetry install` to install dependencies.
5. Run `poetry run pre-commit install` to set up pre-commit hooks.

## Development

- Use `poetry run pytest` to run tests.
- The pre-commit hooks will run automatically on commit, or you can run them manually with `poetry run pre-commit run --all-files`.

## GitHub Actions

The `.github/workflows/pre-commit.yml` file sets up a GitHub Action that runs pre-commit checks on pull requests and pushes to the `main` and `feature/*` branches.