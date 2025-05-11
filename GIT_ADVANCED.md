```markdown
# Advanced Git and GitHub Practice

This repository is for learning and experimenting with advanced Git commands and workflows.

## Git Commands

- **View unstaged and staged changes:**  
  `git diff`  
  `git diff --staged`

- **Undo changes:**  
  `git restore <file>` (Discard changes in working directory)  
  `git restore --staged <file>` (Unstage changes)

- **View commit history as a graph:**  
  `git log --oneline --graph --all`

- **Apply a specific commit from another branch:**  
  `git cherry-pick <commit_hash>`

- **Rebase current branch onto another branch:**  
  `git checkout feature-branch`  
  `git rebase main`

- **Tag a specific commit:**  
  `git tag v1.0.0`  
  `git push origin v1.0.0`

- **Show who last modified each line of a file:**  
  `git blame <filename>`

- **.gitignore file:**  
  To ignore files/folders, create a `.gitignore` file with content like:  
  **pycache**/
  \*.log
  .env
```

```

## Notes

- Use `git diff` to inspect changes before committing.  
- Use `git restore` to discard unwanted edits.  
- Use `git log --graph` to visualize branches and merges.  
- Use `git cherry-pick` for applying specific commits across branches.  
- Use `git rebase` for cleaner commit history (when needed).  
- Use `git tag` to mark important commits or releases.  
- Use `git blame` to track changes made to specific lines.  
- Keep `.gitignore` updated to avoid pushing unnecessary files.
```

