# Sample
Sample project for practicing again Git cmd

---

# Git Commands

### Configuration
```bash
git config --global user.name "sample"
git config --global user.email "email@mail.com"

#Basic Command

git add .                  # Stage all changes
git commit -m "message"    # Commit changes
git commit -am "message"   # to add and commit file
git pull origin main       # Pull latest changes
git push -u origin main    # First time push (sets upstream)
git push                   # Use this after upstream is set
git pull                   # Use this after upstream is set

#Branching cmd

git checkout branchName    # Switch to branch
git checkout -b branchName # Create new branch

# Compare & Merge

git diff branchName        # Check difference with branch
git merge sourceBranchName # Merge source branch into current branch

#Logs & History

git log                       # Show commit history (detailed)
git log --oneline             # Compact view of history
git log --graph --oneline     # Visualize branch/merge history
git reflog                    # Show history of all HEAD changes (even after reset)


## Undo & Reset

git reset --soft HEAD~1       # Undo last commit, keep changes staged
git reset --mixed HEAD~1      # Undo last commit, keep changes unstaged
git reset --hard HEAD~1       # Undo last commit and discard changes
git reset <file>              # Unstage a specific file
git restore <file>            # Discard changes in a file (newer Git versions)




