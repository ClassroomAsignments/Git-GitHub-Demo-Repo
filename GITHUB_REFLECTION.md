# GitHub & Git Practice Assignment - Student Reflection

Please answer the following questions after completing Tasks 1 through 5.

### 1. What is the difference between `git fetch` and `git pull`?
`git fetch` downloads commits and metadata from the remote repository without changing the local working branch, while `git pull` performs a fetch followed by an automatic merge (or rebase) into the current branch.

### 2. How did you resolve the merge conflict in Task 4?
I created a conflict branch with a different greeting in `src/app.py`, then merged it into `main`, opened the file, removed the conflict markers, kept the desired greeting, and committed the resolved file.

### 3. Why is it useful to use `.gitignore` in a software project?
`.gitignore` prevents temporary files, build artifacts, and sensitive local configuration from being tracked in Git, which keeps the repository clean, reduces noise in commits, and avoids accidentally sharing unwanted files.
