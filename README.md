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



