# GitHub-Guide
cheat codes or how to use Git effectively?!

## 📖 Commands

### 🏁 Starting a Repo
```bash
git init                 # Create new repo
git clone <url>          # Clone remote repo
```
### 📦 Staging & Committing
```
git status               # Show changes
git add <file>           # Stage a file
git add .                # Stage all changes
git commit -m "msg"      # Commit staged changes
git commit -am "msg"     # Stage tracked + commit
```
### 🔍 Inspecting History
```
git log --oneline --graph  # Compact history view
git diff                   # Show unstaged changes
git diff --staged          # Show staged vs last commit
```
### 🌿 Branching
```
git branch                 # List branches
git branch <name>          # Create branch
git switch <name>          # Switch branch
git switch -c <name>       # Create + switch
git checkout <name>        # Old way to switch branch
git branch -d <name>       # Delete branch
```
### 🔄 Remote Sync
```
git remote -v              # Show remotes
git pull                   # Update current branch
git pull --rebase          # Rebase instead of merge
git push                   # Push current branch
git push -u origin <branch> # First push + set upstream
```
### 🔀 Merging & Rebasing
```
git merge <branch>         # Merge into current
git rebase <branch>        # Rebase onto branch
git cherry-pick <commit>   # Apply specific commit
```
### ⏪ Undoing Changes
```
git restore <file>         # Discard local changes
git reset <file>           # Unstage file
git reset --hard HEAD      # Reset everything to last commit
git revert <commit>        # Undo commit with new commit
```
### 📂 Stash
```
git stash                  # Stash changes
git stash list             # List stashes
git stash pop              # Apply + remove stash
```
### 🏷️ Tags
```
git tag                    # List tags
git tag <name>             # Create tag
git push origin <name>     # Push tag
```
### 🛠️ Helpers
```
git reflog                 # Show all HEAD history
git clean -fd              # Remove untracked files/dirs
```

## Conclusion
⭐ If this cheat sheet helped you, please consider giving the repo a star, it keeps me motivated to share more like this!

[Handy Reference - click here to download!](Asset/Git-Cheat.jpg)
