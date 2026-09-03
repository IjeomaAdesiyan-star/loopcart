 # 🛒 LoopCart

![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Workflow-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Workflow-181717?logo=github&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automation-2088FF)
![License](https://img.shields.io/badge/License-MIT-green)
> **A hands-on Engineering Workflow project demonstrating Git, GitHub, feature branching, Pull Requests, code review, CI/CD, testing, and deployment.**

---

## ✨ About the Project

**LoopCart** is a Python application that delivers personalised welcome messages to users.

This project is part of a practical **Engineering Workflow** exercise designed to demonstrate how a developer moves from making a code change through testing, code review, merging, and a CI/CD process.

---

## 🎯 Project Purpose

The purpose of LoopCart is to provide a simple, customizable way to greet users with tailored messages, making onboarding smoother and more engaging.

### 🔧 Workflow Practised

- 📥 Cloning a repository
- 🌿 Creating and working with feature branches
- 💻 Writing and testing code
- 📝 Creating meaningful commits
- 🚀 Pushing changes to GitHub
- 🔀 Opening Pull Requests
- 👀 Applying code review feedback
- 🔀 Merging changes into `main`
- 🧪 Running automated tests
- 📦 Building a release artifact
- 🚀 Simulating deployment through CI/CD

---

## 🛠️ Prerequisites

Before getting started, make sure you have:

* Git installed and configured
* Python installed
* Git Bash or another terminal
* A GitHub account

> 💡 **Windows users:** Git Bash can be used to run the Git and Bash commands used in this project.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/IjeomaAdesiyan-star/loopcart.git
```

### 2️⃣ Enter the project directory

```bash
cd loopcart
```

### 3️⃣ Run the application

```bash
python app.py
```

---

## 🔀 Git & GitHub Workflow

The project follows a structured development workflow:

```text
                 🌿 Feature Branch
                       │
                       ▼
                  💻 Make Changes
                       │
                       ▼
                    🧪 Test
                       │
                       ▼
                   📝 Commit
                       │
                       ▼
                  🚀 Push to GitHub
                       │
                       ▼
                🔀 Pull Request
                       │
                       ▼
                 👀 Code Review
                       │
                       ▼
                  ✅ Merge to main
```

---

## 🌿 Branching

Feature branches were used to keep development work separate from the `main` branch.

Example:

```bash
git checkout -b feat/your-feature
```

This approach allows changes to be developed, tested, reviewed, and merged in a controlled workflow.

---

## 🔄 CI/CD Pipeline

The project includes a `ci_cd.sh` script demonstrating a basic CI/CD pipeline.

### Pipeline Flow

```text
🧪 TEST
   ↓
📦 BUILD
   ↓
🚀 DEPLOY
```

### Pipeline stages

**1. 🧪 Test**

The pipeline runs an automated test against the application's greeting function.

**2. 📦 Build**

A release artifact is created during the build stage.

**3. 🚀 Deploy**

The pipeline simulates deployment by placing the release artifact into a production directory.

> ⚙️ The `ci_cd.sh` script demonstrates the basic idea of automating the journey from testing to deployment.

---

## 🧪 Testing

The project uses Python's `assert` functionality to check that the application's greeting function returns the expected result.

Example:

```python
assert greet("test") == "Welcome to LoopCart v1.0, test!"
```

Automated checks help identify problems before changes move further through the workflow.

---

## 📂 Project Structure

```text
loopcart/
│
├── 🐍 app.py
├── 📖 README.md
├── 📝 PR_DESCRIPTION.md
└── ⚙️ ci_cd.sh
```

### 📄 File Overview

| File                | Purpose                    |
| ------------------- | -------------------------- |
| `app.py`            | Main Python application    |
| `README.md`         | Project documentation      |
| `PR_DESCRIPTION.md` | Pull Request documentation |
| `ci_cd.sh`          | CI/CD pipeline script      |

---

## 💻 Git Commands Practised

Some of the Git commands used throughout the workflow include:

```bash
git status
git add
git commit
git push
git fetch
git merge
git branch
git log
git diff
```

These commands were used to track changes, manage branches, collaborate through GitHub, and maintain the project history.

---

## 🤝 Contributing

To contribute:

1. Create a feature branch:

```bash
git checkout -b feat/your-feature
```

2. Make and test your changes.

3. Commit your changes:

```bash
git commit -m "feat: describe your change"
```

4. Push your branch:

```bash
git push -u origin feat/your-feature
```

5. Open a Pull Request and request a review.

6. Apply feedback and merge into `main`.

---

## 📚 What I Learned

This project provided hands-on practice with:

- 🔀 Git branching and merging
- 🐙 GitHub repositories and Pull Requests
- 📝 Meaningful commit messages
- 🧪 Automated testing
- 🔄 CI/CD concepts
- 📦 Build and release processes
- 🚀 Deployment workflows
- 📖 Markdown documentation
- 💻 Working with Git Bash and Python

---

## 📄 License

**MIT License**

---

## 👩🏽‍💻 Engineering Workflow

**Learn → Build → Test → Review → Merge → Automate → Deploy 🚀**
