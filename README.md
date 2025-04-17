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
