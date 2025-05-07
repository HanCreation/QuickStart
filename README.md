# Github & Git Quick Start
This is a quick start guide for Github and Git. Built for myself to help me remember the commands.

## Quick Start for New Repository

### Initialize a new repository
```bash
git init
```

### Add changes to the repository
```bash
git add .
```

### Commit changes to the repository
```bash
git commit -m "Commit message"
```

### Force rename a branch/init main branch
```bash
git branch -M main
```

### Add a remote repository
```bash
git remote add origin <repository-url>
```

### Push to a remote repository
```bash
git push -u origin 
```
---
## For Existing Repository

### Fetch changes from current branch
```bash
git fetch origin
```

### Check current branch
```bash
git branch
```

### Push changes to current branch
```bash
git push origin
```
### Pull changes from a remote branch
```bash
git pull origin <branch-name>
```

### Push changes to a remote branch
```bash
git push origin <branch-name>
```

## Branches

### Create a new branch
```bash
git branch <branch-name>
```

### Switch to a branch
```bash
git checkout <branch-name>
```

### Merge a branch
```bash
git merge <branch-name>
```

### Delete a branch
```bash
git branch -d <branch-name>
```

### Delete a remote branch
```bash
git push origin --delete <branch-name>
```

### Pull changes from a remote branch
```bash
git pull origin <branch-name>
```

### Push changes to a remote branch
```bash
git push origin <branch-name>
```





























