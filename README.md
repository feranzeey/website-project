# Automated Website Deployment with GitHub Actions

## Project Overview

This project demonstrates how to create and deploy a simple HTML website using GitHub and GitHub Actions.

The project includes:

* Basic HTML website
* Git version control
* GitHub repository integration
* Automated deployment workflow using GitHub Actions

---

## Technologies Used

* HTML5
* Git
* GitHub
* GitHub Actions
* Visual Studio Code

---

## Project Structure

```bash
website-project/
│
├── index.html
└── README.md
```

---

##  Setup Steps

### Step 1 — Create Project Folder

```bash
mkdir website-project
cd website-project
```

### Step 2 — Create Website File

Create `index.html`

```html
<!DOCTYPE html>
<html>
<head>
  <title>My DevOps Website</title>
</head>
<body>
  <h1>Hello DevOps World</h1>
</body>
</html>
```

---

##  Initialize Git

```bash
git init
git add .
git commit -m "first commit"
```

---

##  Push to GitHub

```bash
git remote add origin YOUR_GITHUB_REPO_LINK
git branch -M main
git push -u origin main
```

---

## Project Goal

The goal of this project is to practice:

* Git commands
* GitHub workflow
* Basic DevOps automation
* Continuous Integration concepts

---

##  Author

Created by Feranmi
