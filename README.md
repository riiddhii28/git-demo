

```markdown
# Git and GitHub Practice

This repository is for practicing and revising Git and GitHub commands and workflows.

## Git Commands

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
git add .      # stage all changes

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

Branching:
```

git branch                # list branches
git checkout -b branchname  # create and switch
git checkout branchname     # switch only
git merge branchname        # merge into current branch

```

Remote and GitHub:
```

git remote add origin \<repo\_url>
git push -u origin branchname
git pull origin branchname
git remote -v

```

Deleting branches:
```

git branch -d branchname         # delete local branch
git push origin --delete branchname  # delete remote branch

```

Stash changes:
```

git stash
git stash pop

```

Undo and reset:
```

git reset <file>
git reset --hard

```

Clone using:
```

git clone \<repo\_url>

```

## Notes

- Always use `git status` to check changes
- Use branches for experiments
- Merge and handle conflicts carefully
```

## Create a new branch and switch to it (merging)
git checkout -b feature-branch
git add feature.py
git commit -m "Added feature.py in feature branch
git push -u origin feature-branch

git checkout main
git merge feature-branch
git push origin main