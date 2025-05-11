````markdown
# Git and GitHub Practice

This repository is for practicing and revising Git and GitHub commands and workflows.

## Git Basics

```bash
# Initialize a Git repository
git init

# Check status of files
git status

# Stage files
git add <filename>
git add .    # Stage all changes

# Commit changes
git commit -m "Your message"

# View commit history
git log
git log --oneline
````

## Branching and Merging

```bash
# List branches
git branch

# Create and switch to a new branch
git checkout -b feature-branch

# Switch to another branch
git checkout main

# Merge a branch into current branch
git merge feature-branch

# Delete branches
git branch -d feature-branch                  # Delete local branch
git push origin --delete feature-branch       # Delete remote branch
```

## Remote and GitHub

```bash
# Link to remote GitHub repository
git remote add origin <repo_url>

# Push changes to GitHub
git push -u origin branch-name

# Pull latest changes
git pull origin branch-name

# Clone repository
git clone <repo_url>

# Check remotes
git remote -v
```

## Stashing and Reset

```bash
# Stash changes temporarily
git stash
git stash pop

# Undo changes
git reset <file>       # Unstage
git reset --hard       # Discard all changes
```

## Example: Create a New Branch and Merge

```bash
git checkout -b feature-branch
# make changes to feature.py
git add feature.py
git commit -m "Added feature.py in feature branch"
git push -u origin feature-branch

git checkout main
git merge feature-branch
git push origin main
```

## Notes

* Use `git status` often to check changes
* Use branches to work on new features or experiments
* Use meaningful commit messages
* Always pull before pushing to avoid conflicts
* Resolve merge conflicts carefully when they occur

```

