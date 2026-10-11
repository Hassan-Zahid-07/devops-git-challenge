# Proof of Work

## 1. Git Log (git log --oneline)

```
3825a63 (HEAD -> main, origin/main) Update PROOF_OF_WORK.md with final reflection answers
20315b5 Add PROOF_OF_WORK.md with git log and reflection answers
668afce Merge pull request #1 from Hassan-Zahid-07/development
c62e7e7 (origin/development, development) Merge staging into development: resolve deploy.sh conflict
4af8afd (origin/staging, staging) Add staging environment message to deploy.sh
b8a1598 Add development environment message to deploy.sh
ba0b30d first commit: added  deploy.sh and README.md
```

## 2. Reflection Questions

### Q1: What is the difference between Git and GitHub?
Git is a tool that I install on my computer. It tracks the changes in my files and saves the history of my project, even without internet. GitHub is a website where I upload my Git repository so it is stored online. People can also share code and work together there, for example with Pull Requests. So Git works on my laptop, and GitHub works on the internet.

### Q2: Explain the three architecture stages: Working Directory, Staging Area and Local Repository.
The Working Directory is the normal folder on my computer where I create and edit my files. The Staging Area is where I put the files I want to save in my next commit, using `git add`. The Local Repository is where Git stores my commits on my computer after I run `git commit`. So a file moves from the Working Directory to the Staging Area and then to the Local Repository.

### Q3: What is the difference between git stash pop and git stash apply?
Both commands bring back the changes I saved with `git stash`. `git stash pop` restores the changes and also deletes that stash from the list. `git stash apply` restores the changes but keeps the stash in the list. I used `pop` in this activity because I did not need the stash after restoring it.

### Q4: What is the difference between git fetch and git pull?
`git fetch` downloads the latest changes from GitHub but does not change my files. This lets me check the changes first and then decide what to do. `git pull` downloads the changes and merges them into my current branch straight away. So `git pull` is basically `git fetch` plus `git merge`.