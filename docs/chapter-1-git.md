# Chapter 1: Git Basics

Git is a **version control system** — it tracks changes in your code.  
We use it with GitHub to share and submit assignments.


## 🛠 Commands You Need

```bash
git status            # check what changed
git add .             # stage all changes
git commit -m "msg"   # save a snapshot with a message
git push origin main  # upload to GitHub
````

👉 Rule of thumb: **commit early, commit often.**

---

## 🔄 Workflow for This Course

1. **Clone** the repo once:

   ```bash
   git clone <url>
   cd <repo>
   ```
2. **Edit** your files.
3. **Stage + commit** your changes:

   ```bash
   git add .
   git commit -m "added about section"
   ```
4. **Push** to GitHub:

   ```bash
   git push
   ```
5. Repeat steps 2–4 as you keep working.

---

## 📝 Commit Messages

Good commit messages explain what you changed:

* ✅ `"add projects section"`
* ✅ `"style header with flexbox"`
* ❌ `"stuff"`, `"final"`, `"fix"`

---

## ⚡ Cheatsheet

* See changes → `git status`
* Undo staged file → `git reset <file>`
* Undo local edits → `git checkout -- <file>`
* View history → `git log --oneline`

