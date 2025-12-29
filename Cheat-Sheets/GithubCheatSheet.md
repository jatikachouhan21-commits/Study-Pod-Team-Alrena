# GitHub Command Cheat Sheet

Here's a comprehensive **GitHub Command Cheat Sheet** 🐙💻 — focused on Git CLI commands used with GitHub for version control, collaboration, and repository management.

---

## 🔧 Setup & Configuration

| Command                                            | Description                   |
| -------------------------------------------------- | ----------------------------- |
| `git config --global user.name "Your Name"`        | Set your GitHub username      |
| `git config --global user.email "you@example.com"` | Set your GitHub email         |
| `git config --list`                                | View current Git config       |
| `ssh-keygen -t ed25519 -C "you@example.com"`       | Generate SSH key for GitHub   |
| `git config --global credential.helper cache`      | Cache credentials temporarily |

---

## 📁 Repository Basics

| Command                                      | Description               |
| -------------------------------------------- | ------------------------- |
| `git init`                                   | Initialize a new Git repo |
| `git clone https://github.com/user/repo.git` | Clone a remote repo       |
| `git remote -v`                              | Show remote URLs          |
| `git remote add origin URL`                  | Add remote origin         |
| `git status`                                 | Show current changes      |
| `git log`                                    | View commit history       |

---

## 📦 Staging & Committing

| Command                    | Description                |
| -------------------------- | -------------------------- |
| `git add filename`         | Stage a file               |
| `git add .`                | Stage all changes          |
| `git commit -m "message"`  | Commit staged changes      |
| `git commit -am "message"` | Add & commit tracked files |

---

## 🔁 Branching & Merging

| Command                       | Description               |
| ----------------------------- | ------------------------- |
| `git branch`                  | List branches             |
| `git branch branch_name`      | Create a new branch       |
| `git checkout branch_name`    | Switch to a branch        |
| `git checkout -b branch_name` | Create & switch to branch |
| `git merge branch_name`       | Merge branch into current |
| `git branch -d branch_name`   | Delete a branch           |

---

## 🚀 Pushing & Pulling

| Command                          | Description           |
| -------------------------------- | --------------------- |
| `git push origin branch_name`    | Push to remote        |
| `git pull origin branch_name`    | Pull from remote      |
| `git fetch`                      | Fetch latest changes  |
| `git push -u origin branch_name` | Push and set upstream |

---

## 🧹 Undo & Reset

| Command                      | Description                   |
| ---------------------------- | ----------------------------- |
| `git reset filename`         | Unstage a file                |
| `git checkout -- filename`   | Discard changes in file       |
| `git revert commit_id`       | Undo a commit (safe)          |
| `git reset --hard commit_id` | Reset to commit (destructive) |
| `git reset --soft HEAD~1`    | Reset to commit (safe)        |

---

## 📄 GitHub-Specific Actions

| Command              | Description             |
| -------------------- | ----------------------- |
| `gh auth login`      | Authenticate GitHub CLI |
| `gh repo create`     | Create GitHub repo      |
| `gh issue list`      | List issues             |
| `gh pr create`       | Create pull request     |
| `gh pr checkout 123` | Checkout PR #123        |

---
