# Connect a GitHub Repo with AWS – DevOps Challenge Day 2 🚀

**Project 2 of the 7-Day DevOps Challenge**  
Learn the basics of Git, GitHub, and connect your web app to a remote repository for source control.

---

## 📚 Overview

In this project, I connected my Java web application (hosted on an Amazon EC2 instance) to a GitHub repository to enable version control and collaboration using Git.

This is **Day 2 of the 7-Day DevOps Challenge**, focused on building foundational skills in DevOps — particularly Git, GitHub, and basic version control workflows.

---

## 💡 What I Learned

- How to install and configure Git on an EC2 instance
- The difference between Git (local) and GitHub (remote/cloud)
- How to:
  - Initialize a Git repository
  - Connect a local repo to a remote GitHub repo
  - Stage, commit, and push code changes
  - Use a personal access token (PAT) to authenticate with GitHub

---

## 🧱 Tech Stack

- **Java Web App** (JSP)
- **Amazon EC2** (Amazon Linux 2023)
- **Git + GitHub**
- **VS Code** (with Remote SSH)
- **Terminal / CLI**

---

## 📁 Project Setup

1. **Launch EC2 Instance** (Amazon Linux)
2. **Connect to EC2 via VS Code SSH**
3. **Install Git on EC2**
   ```bash
   sudo dnf update -y
   sudo dnf install git -y
   git --version
   ```
4. **Initialize Git in project folder**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
5. **Connect to GitHub repo**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin master
   ```
6. **Authenticate with GitHub Token** (replacing password)

---

## 📸 Screenshots

- ✅ Git installed and verified
- ✅ GitHub repository created
- ✅ Project committed and pushed to GitHub
- ✅ Second commit made after editing `index.jsp`

---

## 🧠 Key Takeaways

> Git is your **version control system**.  
> GitHub is your **cloud storage + collaboration tool**.  
> The `git init` + `add` + `commit` + `push` flow is the **heartbeat of DevOps version control**.  
> Connecting your local codebase with GitHub is an essential DevOps skill.

---

## 🌐 Repository Name Suggestion

If you're using GitHub, I suggest naming your repo:
```
nextwork-web-project
```
or
```
connect-github-repo-aws
```

---

## ✅ Status

✔️ Project Complete – Day 2 of the 7-Day DevOps Challenge.

Next up: Continuous Integration with AWS CodeBuild 🔧

---

## 📌 Author

**Rogen Magdasal**  
DevOps Learner | AWS Cloud Enthusiast