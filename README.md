

```markdown
# Git and GitHub Practice

This repository is for practicing and revising Git and GitHub commands and workflows.

## Git Basics

Initialize a Git repository:  
```

git init

```

Check status of files:  
```

git status

```

Stage files:  
```

git add <filename>
git add .          # Stage all changes

```

Commit changes:  
```

git commit -m "Your message"

```

View commit history:  
```

git log
git log --oneline

```

## Branching and Merging

List branches:  
```

git branch

```

Create and switch to a new branch:  
```

git checkout -b feature-branch

```

Switch between branches:  
```

git checkout main

```

Merge branch into current branch:  
```

git merge feature-branch

```

Delete branches:  
```

git branch -d feature-branch            # Local
git push origin --delete feature-branch # Remote

```

## Remote and GitHub

Link to remote:  
```

git remote add origin \<repo\_url>

```

Push changes:  
```

git push -u origin branch-name

```

Pull changes:  
```

git pull origin branch-name

```

Clone repository:  
```

git clone \<repo\_url>

```

Check remotes:  
```

git remote -v

```

## Stash and Reset

Stash changes temporarily:  
```

git stash
git stash pop

```

Undo changes:  
```

git reset <file>
git reset --hard

```

## Example: Create a New Branch and Merge

# Create and switch to a new branch
git checkout -b feature-branch

# Make changes and stage a file
git add feature.py

# Commit the changes
git commit -m "Added feature.py in feature branch"

# Push the branch to GitHub
git push -u origin feature-branch

# Switch back to main branch
git checkout main

# Merge the feature branch into main
git merge feature-branch

# Push the updated main branch to GitHub
git push origin main
