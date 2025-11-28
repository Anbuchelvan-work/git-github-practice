# Git Commands — Day 1

## Basic Commands
- git init → initialize a repository
- git clone <url> → download a repo
- git status → check changes
- git add <file> → stage changes
- git commit -m "message" → save changes
- git push → upload changes
- git pull → download latest changes

## Branching
- git branch → list branches
- git branch <name> → create branch
- git checkout <name> → switch branch
- git merge <name> → merge branch

## Notes
- Always check `git status` before committing.
- Use meaningful commit messages.

## Git Branching (Important)

### Create a new branch
```
git branch feature-login
```

### Switch to a branch
```
git checkout feature-login
```

### Create + switch (shortcut)
```
git checkout -b feature-login
```

### Merge a branch into main
```
git checkout main
git merge feature-login
```

### Delete a branch
```
git branch -d feature-login
```

### Notes
- Always create new features in separate branches.
- Never commit directly to `main`.
- Use pull requests for clean workflow.
```
## Git Branching (Important)

### Create a new branch
```
git branch feature-login
```

### Switch to a branch
```
git checkout feature-login
```

### Create + switch (shortcut)
```
git checkout -b feature-login
```

### Merge a branch into main
```
git checkout main
git merge feature-login
```

### Delete a branch
```
git branch -d feature-login
```

### Notes
- Always create new features in separate branches.
- Never commit directly to `main`.
- Use pull requests for clean workflow.
```
