# XGBoost MLOps Practice Project

## Project Overview

This project is being developed alongside KodeKloud's 100 Days of MLOps course.

The goal is to practice MLOps concepts by gradually building an XGBoost-based machine learning application.

## Technology Stack

- Python 3.13
- NumPy and Pandas — Data processing
- Scikit-learn — Preprocessing and evaluation
- XGBoost — Machine learning algorithm
- MLflow — Experiment tracking
- Joblib — Model serialization
- Pytest — Automated testing
- FastAPI and Uvicorn — Model serving

## Dependency Management

We use `uv` to manage Python dependencies.

- `requirements.in` contains direct dependencies.
- `requirements.txt` contains pinned dependencies, including transitive dependencies.

### Setup (Windows PowerShell)

Create a virtual environment:

```powershell
py -m uv venv .venv --python 3.13
```

Install dependencies:

```powershell
py -m uv pip sync requirements.txt --python .venv
```

### Updating Dependencies

After modifying `requirements.in`, regenerate the lockfile:

```powershell
py -m uv pip compile requirements.in -o requirements.txt
```

Review the changes and test compatibility before committing an update.

## Learning Progress

- [x] Dependency specification with `requirements.in`
- [x] Dependency compilation with `uv`
- [ ] Virtual environment setup and dependency installation
- [ ] Git and `.gitignore`
- [ ] Makefile automation
- [ ] Code formatting and testing
- [ ] Model training and experiment tracking
- [ ] Docker and deployment
- [ ] CI/CD and monitoring

## Project Status

Work in progress — MLOps fundamentals and environment setup.
