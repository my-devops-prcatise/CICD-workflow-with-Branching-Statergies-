
# CI/CD Pipeline with Branching Strategy (POC)

## 📌 Project Overview

This project demonstrates a simple CI/CD pipeline using GitHub Actions with a Git branching strategy.

The pipeline automatically:

* Runs tests when code is pushed
* Validates pull requests
* Simulates deployment when code is merged to main

---

## 🚀 Technologies Used

* Python
* GitHub Actions
* Git Branching Strategy
* Pytest

---

## 🌿 Branching Strategy

This project follows a simple GitFlow model.

### Branch Structure

* **main** → Production code
* **develop** → Integration branch
* **feature/*** → New features

### Workflow

```
feature → develop → main → deploy
```

---

## ⚙️ CI/CD Flow

1. Developer creates feature branch
2. Push code to GitHub
3. GitHub Actions runs tests automatically
4. If tests pass → merge allowed
5. Merge to main triggers deployment

---

## ▶️ How to Run Locally

Install dependencies:

```
pip install -r requirements.txt
```

Run tests:

```
pytest
```

---

## 📦 Pipeline Stages

* Checkout code
* Setup Python
* Install dependencies
* Run tests
* Deploy (simulation)

---

## 🎯 Purpose of this POC

* Understand CI/CD workflow
* Learn Git branching strategy
* Automate testing process
* Demonstrate DevOps pipeline
