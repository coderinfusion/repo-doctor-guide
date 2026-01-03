# repo-doctor-guide
Common reasons code repositories fail to run (and how to fix them)

# Your Repo Won’t Run. Here’s Why.

If your project:
- installs fine but won’t start
- throws errors that make no sense
- worked in the tutorial but not on your machine

You’re not bad at coding.  
This is normal.

---

## The 5 Most Common Reasons Repos Fail

### 1️⃣ Missing Environment Variables
- `.env` file missing or not loaded
- app starts then crashes immediately

**Fix:** confirm the file exists, is loaded, and restart the app.

---

### 2️⃣ Dependency Mismatch
- `module not found`
- version conflicts
- works on one machine, not another

**Fix:** delete dependencies and reinstall cleanly.

---

### 3️⃣ Wrong Runtime Version
- weird syntax errors
- works for others but not you

**Fix:** check Node / Python version matches the project.

---

### 4️⃣ Port Already in Use
- app won’t start
- error mentions port `3000`, `8000`, or `50
