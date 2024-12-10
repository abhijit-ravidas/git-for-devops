# Git Commands Reference

This document provides a categorized list of commonly used Git commands for various tasks.  

---

## 1. **Getting Started with Git**
### Initialize a Git repository
```bash
git init

# Clone an existing repository

git clone <repository_url>

## 2. **Working with Changes**
# Check the status of the working directory

git status

# Add changes to the staging area

git add <file_name>

# Add all changes to the staging area

git add .

# Commit changes

git commit -m "Your commit message"

##3. **Branch Management**
# Create a new branch

git branch <branch_name>

# Switch to a branch

git checkout <branch_name>

# Create and switch to a new branch

git checkout -b <branch_name>

# List all branches

git branch


## 4. **Merging and Rebasing**
# Merge a branch into the current branch

git merge <branch_name>

# Rebase the current branch onto another branch

git rebase <branch_name>

##5. **Viewing History**
# View commit history

git log

# View a condensed commit history (one-line format)

git log --oneline

## 6. **Remote Repositories**
# Add a remote repository

git remote add origin <repository_url>

# Push changes to the remote repository

git push origin <branch_name>

# Pull changes from the remote repository

git pull origin <branch_name>

## 7. **Undoing Changes**
# Undo the last commit (keep changes in the working directory)

git reset --soft HEAD~1

# Discard changes in a file
git checkout -- <file_name>

##8. **Tagging**
#Create a new tag

git tag <tag_name>

# Push a tag to the remote repository

git push origin <tag_name>


## 9. **Advanced Commands**
# Stash changes

git stash

# Apply stashed changes

git stash apply

# Resolve merge conflicts

git mergetool

##10. **Cleanup**
#Delete a branch locally

git branch -d <branch_name>

# Delete a branch remotely

git push origin --delete <branch_name>

Notes
Replace placeholders (e.g., <branch_name>, <repository_url>, <file_name>) with your specific values.
Use these commands cautiously to avoid unintentional loss of data.
vbnet
Copy code

