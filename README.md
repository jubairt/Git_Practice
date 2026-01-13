# 📘 Git Learning Project

This repository is a **hands-on Git learning project**.  
It covers Git fundamentals, branching, merging, undoing changes, and working with remote repositories (GitHub).

The goal is to **understand Git practically**, not just theoretically.

---

## 📌 What I Learned

- Initializing a Git repository
- Tracking files and committing changes
- Understanding commit history
- Working with branches
- Merging branches
- Undoing mistakes safely
- Working with remote repositories (GitHub)
- Fetching, pulling, and comparing changes

---

## 🚀 Git Commands Used (With Explanation)

### 🔹 Repository Initialization
```bash
git init
```

### 🔹 Adding Files to Staging Area
```bash
git add .
```

### 🔹 Committing Changes
```bash
git commit -m "first commit"
```

### 🔹 Checking Repository Status
```bash
git status
```

### 🔹 Viewing Commit History
```bash
git log
git log --oneline
```

---

## 🌿 Branching

### 🔹 View Existing Branches
```bash
git branch
```

### 🔹 Change name of the branch
```bash
git branch -M main
```

### 🔹 Create a New Branch
```bash
git branch feature-x
```

### 🔹 Switch to a Branch
```bash
git checkout feature-x
# or
git switch feature-x
```

### 🔹 Merge a Branch (run from main/master)
```bash
git merge feature-x
```

---

## ⏪ Time Travel & Fixing Mistakes

### 🔹 Create a Branch from an Old Commit
```bash
git checkout -b fix-from-old 1300f39
```

### 🔹 Restore File to Last Commit
```bash
git restore notes.txt
```

### 🔹 Remove Last Commit (Keep Changes)
```bash
git reset --soft HEAD~1
```

### 🔹 Remove Last Commit (Delete Changes)
```bash
git reset --hard HEAD~1
```

### 🔹 Safely Undo a Commit
```bash
git revert <commit-hash>
```

---

## 🌍 Working with Remote Repositories (GitHub)

### 🔹 Fetch Remote Changes (Without Applying)
```bash
git fetch origin
```

### 🔹 View Fetched Changes
```bash
git log origin/main
git diff main origin/main
```

### 🔹 Fetch + Merge Remote Changes
```bash
git pull origin main
```

---

## 🧠 Key Concepts Learned

- Working Directory → Staging Area → Commit
- Branches are pointers to commits
- Fast-forward vs 3-way merge
- Detached HEAD state
- Reset vs Revert
- Fetch vs Pull
- Safe vs destructive Git commands

---

## 🎯 Purpose of This Repository

This repo is meant for:
- Learning Git step by step
- Practicing real commands
- Understanding mistakes and recovery
- Building strong Git fundamentals

---

## 🙌 Author

**Jubair Abdulla**  
Learning Git the right way — by practicing 🚀
