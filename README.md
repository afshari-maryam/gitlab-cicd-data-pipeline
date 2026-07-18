# gitlab-cicd-data-pipeline

A small data-processing project set up with a full GitLab CI/CD workflow:
automated linting, testing, and build steps triggered on every commit.

## Goals
- Practice GitLab CI/CD pipelines (.gitlab-ci.yml)
- Automate code quality checks (flake8) and unit tests (pytest)
- Build a reproducible pipeline that runs the same way locally and in CI

## Tech Stack
- Python
- GitLab CI/CD
- pytest, flake8

## Status
🚧 In progress

## Structure (planned)
- `.gitlab-ci.yml` — pipeline definition (lint → test → build)
- `src/` — pipeline source code
- `tests/` — unit tests
