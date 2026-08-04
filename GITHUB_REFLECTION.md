# GitHub & Git Practice Assignment - Student Reflection

### 1. What is the difference between `git fetch` and `git pull`?
`git fetch` downloads commits, files, and refs from a remote repository into your local repository without modifying your current working files. In contrast, `git pull` performs a `git fetch` followed immediately by a `git merge` to update your current branch with remote changes.

### 2. How did you resolve the merge conflict in Task 4?
To resolve the merge conflict in Task 4, I identified the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) inserted into `src/app.py` by Git. I carefully selected the intended greeting implementation, deleted all conflict marker lines, saved the clean file, and committed the resolution with `git commit`.

### 3. Why is it useful to use `.gitignore` in a software project?
A `.gitignore` file prevents untracked temporary files, logs, environment variables, and build artifacts from being accidentally committed into the version control history. This keeps the repository clean, reduces unnecessary diff bloat, and prevents sensitive credentials from leaking.
