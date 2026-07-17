# Student Management System

## Project Description

This project is a simple Student Management System developed using Python. It demonstrates the use of Git, GitHub, GitHub Actions, and Pytest for version control, collaboration, automated testing, and continuous integration.

## Features

- Add Student
- Remove Student
- Search Student
- Update Student
- Automated testing using Pytest
- Continuous Integration using GitHub Actions

## Project Structure

```
student-management-system/
│── student.py
│── test_student.py
│── requirements.txt
│── README.md
└── .github/
    └── workflows/
        └── python.yml
```

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/nitimehta20/student-management-system.git
```

### 2. Open the Project

```bash
cd student-management-system
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Tests

```bash
pytest
```

---

# Git Commands Used

Initialize Git Repository

```bash
git init
```

Check Repository Status

```bash
git status
```

Add Files

```bash
git add .
```

Commit Changes

```bash
git commit -m "Initial project structure"
```

Rename Branch

```bash
git branch -M main
```

Create Feature Branch

```bash
git checkout -b feature-student-search
```

Push Main Branch

```bash
git push -u origin main
```

Push Feature Branch

```bash
git push -u origin feature-student-search
```

Merge Pull Request

Performed through GitHub after all workflow checks passed.

---

# GitHub Actions Workflow

The project uses GitHub Actions for Continuous Integration (CI).

Whenever code is pushed or a Pull Request is created, GitHub Actions automatically:

1. Checks out the repository.
2. Sets up Python.
3. Installs project dependencies.
4. Executes all Pytest test cases.
5. Reports whether the workflow passes or fails.

If any test fails, the workflow is marked as failed. After fixing the issue and pushing the changes again, the workflow passes successfully.

---

# Technologies Used

- Python
- Git
- GitHub
- GitHub Actions
- Pytest

---

# Author

**Niti Mehta**

B.Sc. Data Science and Business Analytics

Patkar Varde College