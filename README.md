# 🛡️ Removing a Sensitive File from a Git Repository

Sometimes sensitive files like `.env` may accidentally get pushed to a public or private repository. Here's how to **remove them safely** from your repository and prevent this from happening again.

---

## ⚙️ Step-by-Step Guide to Remove a File from Git Repo

### 📌 Example: We want to remove `.env` from the repository

---

### ✅ Step 1: Untrack the file (without deleting it locally)

```bash
git rm --cached .env
```

### ✅ Step 2: Commit the change

```bash
git commit -m "Remove .env file from version control"
```

### ✅ Step 3: Push the changes to GitHub

```bash
git push origin main
```

### ✅ Step 4:Add .env to .gitignore

```bash
echo .env >> .gitignore
git add .gitignore
git commit -m "Add .env to .gitignore"
git push origin main

```

✅ Done!
You’ve now removed the sensitive file from your Git repo and protected it from future commits. 🛡️

```

```
