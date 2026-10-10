# Proof of Work

## 1. Git Log (git log --oneline)

```
668afce (HEAD -> main, origin/main) Merge pull request #1 from Hassan-Zahid-07/development
c62e7e7 (origin/development, development) Merge staging into development: resolve deploy.sh conflict
4af8afd (origin/staging, staging) Add staging environment message to deploy.sh
b8a1598 Add development environment message to deploy.sh
ba0b30d first commit: added  deploy.sh and README.md
```

## 2. Reflection Questions

### Q1: What is the difference between Git and GitHub?
Git is a tool that I install on my computer to track changes in my files. It keeps the full history of my project, and it works even without internet. GitHub is a website that stores Git repositories online. It helps people work together with features like Pull Requests. So Git is the tool, and GitHub is the place where the project is shared.

### Q2: Explain the three architecture stages: Working Directory, Staging Area and Local Repository.
The Working Directory is the folder on my computer where I create and edit my files. The Staging Area is a waiting area where I pick which changes I want in my next commit, using `git add`. The Local Repository is where Git saves commits permanently on my computer, using `git commit`. A file moves in this order: Working Directory, then Staging Area, then Local Repository. This lets me choose exactly what gets saved.

### Q3: What is the difference between git stash pop and git stash apply?
Both commands bring my stashed changes back into my files. `git stash pop` brings the changes back and then removes that stash from the list. `git stash apply` brings the changes back but keeps the stash in the list. I can use `apply` when I want to reuse the same stash again, for example on another branch. I use `pop` when I am done with the stash.

### Q4: What is the difference between git fetch and git pull?
`git fetch` downloads new changes from GitHub but does not change my files or my current branch. It lets me look at the updates first before I decide what to do. `git pull` downloads the changes and also merges them into my current branch right away. So `git pull` is like `git fetch` plus `git merge`. Fetch is safer, and pull is faster.