# 🚀 Selenium Automation Framework (Python + Pytest)

A scalable and production-ready Selenium Test Automation Framework built using modern automation best practices.

---

## 🧰 Tech Stack

- 🐍 Python
- 🌐 Selenium WebDriver
- 🧪 Pytest
- 🧱 Page Object Model (POM)
- 🧹 Pre-commit Hooks (isort, formatting)
- 📊 HTML Reports

---

## 📁 Project Structure

```
selenium_framework/
│
├── pageObjects/        # Page classes (POM implementation)
├── tests/              # Test cases
├── testData/           # Test data files
├── utilities/          # Reusable helpers & custom utilities
├── reports/            # Test execution reports
├── requirements/       # Dependency files
│
├── .gitignore
├── .isort.cfg
├── .pre-commit-config.yaml
└── README.md
```

---

## 🏗 Framework Design Principles

✔ Page Object Model for maintainability  
✔ Clean folder structure  
✔ Reusable utility layer  
✔ Scalable architecture  
✔ Git pre-commit code quality enforcement  
✔ Production-ready project layout  

---

## ⚙️ Setup Guide

### 1️⃣ Clone Repository

```
git clone https://github.com/YOUR_USERNAME/selenium_framework.git
cd selenium_framework
```

---

### 2️⃣ Create Virtual Environment

**Mac / Linux**
```
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**
```
python -m venv .venv
.venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```
sh requirements/repo_req.sh
or
pip install -r requirements/requirements.txt
```

---

### 4️⃣ Install Pre-Commit Hooks

```
pip install pre-commit
pre-commit install
```

---

## ▶️ Running Tests

Run all tests:
```
pytest
```

Run specific test:
```
pytest tests/test_login.py
```

Run with verbose output:
```
pytest -v
```

Generate HTML report:
```
pytest --html=reports/report.html
```

---

## 🧠 Framework Highlights

- Structured Page Object implementation
- Clean separation between tests and page logic
- Centralized utilities for reusable actions
- Easily extendable for API + UI hybrid frameworks
- Ready for CI/CD integration

---

## 🔄 Branch Strategy

- `master` → Stable production branch  
- `release_v1` → Feature development branch  

---

## 📌 Future Enhancements

- CI/CD Integration (GitHub Actions)
- Dockerized execution
- Parallel execution setup
- Allure Reporting integration
- Cross-browser support

---

## 👨‍💻 Author

Shahnawaz Kakar  
Automation Engineer | Python | Selenium | Framework Architect  

---

## ⭐ If You Like This Project

Give it a star ⭐ on GitHub and feel free to fork & enhance it.

---

Happy Testing 🚀
