# 🚀 Git Commands Every Developer Should Know

A complete hands-on guide for developers to understand and practice essential Git commands — from configuring Git to resolving merge conflicts.

---

## 🧩 1. Configure Git (only once per machine)

```bash
git config --global user.name "your-user-name"     # Set your username
git config --global user.email "your-email-id"     # Set your email
git config --list                                  # Verify your configuration
```

---

## 🏗️ 2. Create a New Repository

1. Go to 👉 [https://github.com/new](https://github.com/new)  
2. Create a new repository (example: `collab-demo`)  
3. Add a simple README file  
4. Copy the repository HTTPS URL

---

## 💻 3. Clone Repository to Local Machine

```bash
git clone https://github.com/username/repo-name.git   # Clone remote repo
cd repo-name                                          # Move into repo folder
```

---

## 📋 4. Check Repository Status

```bash
git status      # See which files are modified or untracked
```

---

## 🌿 5. Create and Switch to a New Branch

```bash
git branch my-feature-branch     # Create a new branch
git checkout my-feature-branch   # Switch to that branch
# OR combine both steps:
git checkout -b my-feature-branch
```

---

## ✏️ 6. Make Changes and Commit

```bash
git status                      # Check modified files
git add .                       # Stage all changes
git commit -m "Meaningful commit message"  # Commit changes
```

---

## 🚀 7. Push Your Branch to GitHub

```bash
git push origin my-feature-branch   # Push your branch to remote
```

---

## 🔄 8. Pull Latest Changes from Main Branch

```bash
git pull origin main   # Fetch and merge latest code from main
```

---

## 🔀 9. Merge Main into Your Branch (to stay updated)

```bash
git checkout my-feature-branch   # Ensure you're on your branch
git merge main                   # Merge latest main branch into yours
```

---

## 🧾 10. Create a Pull Request (PR)

1. Go to your GitHub repository  
2. Click **"Compare & Pull Request"**  
3. Add a title and description  
4. Click **"Create Pull Request"**

---

## ✅ 11. Merge the Pull Request

1. Go to the **Pull Requests** tab  
2. Review changes  
3. Click **“Merge Pull Request” → “Confirm Merge”**

---

## 🧹 12. Delete the Branch (after merging)

```bash
git branch -d my-feature-branch             # Delete branch locally
git push origin --delete my-feature-branch  # Delete branch remotely
```

---

## 📜 13. View Commit History

```bash
git log           # Show detailed commit history
git log --oneline # Show compact commit messages
```

---

## 🩹 14. Undo / Fix Mistakes

```bash
git restore filename          # Undo changes in a specific file
git reset --soft HEAD~1       # Undo last commit but keep changes staged
git reset --hard HEAD~1       # Undo last commit and remove changes
```

---

## ⚔️ 15. Resolve Merge Conflicts

```bash
git status                # Identify conflicted files
# Open conflicted files and fix manually
git add <resolved-file>   # Mark as resolved
git commit                # Finalize the merge
```

---

## ⚡ 16. Useful Shortcuts

```bash
git branch        # List all branches
git checkout main # Switch back to main branch
git fetch         # Fetch updates without merging
git diff          # Show file differences
```

---

### 🧠 Pro Tip
Always pull the latest code before you start working:
```bash
git pull origin main
```

---

### 📚 Author
**Divya J**  
_A simple and comprehensive Git guide for collaborative development._

---

### 🌟 License
This guide is open for educational use — feel free to fork and modify.
