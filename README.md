# My Project

This is a boilerplate Python project using uv, pre-commit, and GitHub Actions.

## Setup

1. Make sure you have Python 3.12 installed.
2. Install uv: https://github.com/astral-sh/uv#installation
3. Clone this repository.
4. Run `uv pip install -r requirements.txt` to install dependencies.
5. Run `uv pip install pre-commit` to install pre-commit.
6. Run `pre-commit install` to set up pre-commit hooks.

## Development

- Use `python -m pytest` to run tests.
- The pre-commit hooks will run automatically on commit, or you can run them manually with `pre-commit run --all-files`.

## GitHub Actions

The `.github/workflows/pre-commit.yml` file sets up a GitHub Action that runs pre-commit checks on pull requests and pushes to the `main` and `feature/*` branches.