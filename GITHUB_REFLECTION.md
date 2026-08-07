# GitHub & Git Practice Assignment - Student Reflection

Please answer the following questions after completing Tasks 1 through 5.

### 1. What is the difference between `git fetch` and `git pull`?
`git fetch` downloads commits, files, and refs from a remote repository into your local repository
  without merging them into your working branch. In contrast, `git pull` runs `git fetch` followed
  immediately by `git merge`, automatically integrating remote changes into your local branch.
    
### 2. How did you resolve the merge conflict in Task 4?
    In Task 4, I identified the conflict in `src/app.py`, opened the file in my editor, and deleted all
  conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`). I then combined the greeting functions cleanly,
  saved the file, staged it with `git add`, and finalized the merge commit.
    
### 3. Why is it useful to use `.gitignore` in a software project?
    A `.gitignore` file prevents temporary build artifacts, compiled bytecode (`*.pyc`), log files (`*.
  log`), and sensitive credentials from being committed into Git. This keeps the repository lightweight,
  clean, and secure.
