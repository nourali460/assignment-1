# Git Basics

Git is a **distributed version control system** used to track changes in source code during software development. It enables multiple developers to work on a project simultaneously, keeping history and allowing collaboration efficiently.

---

## 📦 Installation

### Windows
Install [Git for Windows](https://git-scm.com/download/win) and use Git Bash.

### macOS
```bash
brew install git
```

### Linux (Debian-based)
```bash
sudo apt update
sudo apt install git
```

---

## 🔧 Initial Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

## 🆕 Starting a Repository

### Create a new repository
```bash
git init
```

### Clone an existing repository
```bash
git clone https://github.com/username/repo.git
```

---

## 📁 Basic Workflow

1. Modify files in your working directory.
2. Stage the changes with:
    ```bash
    git add filename   # or git add . to add all
    ```
3. Commit the changes:
    ```bash
    git commit -m "Your commit message"
    ```
4. Push changes to a remote repository:
    ```bash
    git push origin main
    ```

---

## 🔍 Checking Status & History

### See what's changed
```bash
git status
```

### View commit history
```bash
git log
```

---

## 🌱 Branching

### Create a branch
```bash
git branch new-branch
```

### Switch to a branch
```bash
git checkout new-branch
```

### Create + switch
```bash
git checkout -b new-branch
```

---

## 🔄 Merging & Pulling

### Merge a branch into the current branch
```bash
git merge branch-name
```

### Pull changes from remote
```bash
git pull
```

---

## ❌ Undoing Changes

### Unstage a file
```bash
git reset filename
```

### Undo last commit (keep changes)
```bash
git reset --soft HEAD~1
```

### Discard local changes
```bash
git checkout -- filename
```

---

## 🌐 Remote Shortcuts

### Add a new remote
```bash
git remote add origin https://github.com/username/repo.git
```

### View remotes
```bash
git remote -v
```

---

## ✅ Good Practices

- Commit often with meaningful messages
- Use `.gitignore` to exclude files/folders
- Branch for features or bug fixes
- Pull regularly to stay in sync

---

## 📚 Learn More

- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Docs](https://docs.github.com/en/get-started/quickstart)

