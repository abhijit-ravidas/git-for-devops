# Git Commands Reference

This document provides a categorized list of commonly used Git commands for various tasks.  

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a developer and want to keep every version of your code/project (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use.

- All the commands used for Git
- Compatibility with GitHub
- ✨Magic ✨
  
---

Set global username and email for Git (Locally).

git config --global user.name "<your username>"
git config --global user.email "<your email>"

## 1. **Getting Started with Git**
### Initialize a Git repository

```sh
git init
```
# Clone an existing repository
```sh
git clone <repository_url>
```

## 2. **Working with Changes**
# Check the status of the working directory

```sh
git status
```
# Add changes to the staging area

```sh
git add <file_name>
```

# Add all changes to the staging area
```sh
git add .
```
# Commit changes

```sh
git commit -m "Your commit message"
```

##3. **Branch Management**
# Create a new branch

```sh
git branch <branch_name>
```

# Switch to a branch

```sh
git checkout <branch_name>
```

# Create and switch to a new branch

```sh
git checkout -b <branch_name>
```

# List all branches

```sh
git branch
```

## 4. **Merging and Rebasing**
# Merge a branch into the current branch

```sh
git merge <branch_name>
```

# Rebase the current branch onto another branch

```sh
git rebase <branch_name>
```

##5. **Viewing History**
# View commit history

```sh
git log
```

# View a condensed commit history (one-line format)

```sh
git log --oneline
```

## 6. **Remote Repositories**
# Add a remote repository

```sh
git remote add origin <repository_url>
```

# Push changes to the remote repository

```sh
git push origin <branch_name>
```

# Pull changes from the remote repository

```sh
git pull origin <branch_name>
```

## 7. **Undoing Changes**
# Undo the last commit (keep changes in the working directory)

```sh
git reset --soft HEAD~1
```
# Discard changes in a file

```sh
git checkout -- <file_name>
```
##8. **Tagging**
#Create a new tag

```sh
git tag <tag_name>
```
# Push a tag to the remote repository

```sh
git push origin <tag_name>
```

## 9. **Advanced Commands**
# Stash changes

```sh
git stash
```

# Apply stashed changes

```sh
git stash apply
```

# Resolve merge conflicts

```sh
git mergetool
```

##10. **Cleanup**
#Delete a branch locally

```sh
git branch -d <branch_name>
```

# Delete a branch remotely

```sh
git push origin --delete <branch_name>
```

Happy Learning! :) 

