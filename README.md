# Basic Git Commands

## Setup & Configuration
- `git config --global user.name "Your Name"`  
- `git config --global user.email "you@example.com"`

## Repository Management
- `git init` → Initialize a new Git repository  
- `git clone <repo-url>` → Clone an existing repository  

## Staging & Committing
- `git status` → Show repo status  
- `git add <file>` → Stage a file  
- `git add .` → Stage all changes  
- `git commit -m "message"` → Commit staged changes  

## Branching & Merging
- `git branch` → List branches  
- `git branch <name>` → Create a new branch  
- `git checkout <name>` → Switch to a branch  
- `git merge <branch>` → Merge a branch into current branch  

## Remote Repositories
- `git remote -v` → Show remote URLs  
- `git push origin <branch>` → Push changes to remote  
- `git pull origin <branch>` → Pull changes from remote  

## History & Logs
- `git log` → Show commit history  
- `git diff` → Show changes between commits or working directory  
- `git show <commit>` → Show details of a commit  

## Undo & Reset
- `git reset <file>` → Unstage a file  
- `git checkout -- <file>` → Discard changes in a file  
- `git revert <commit>` → Undo a commit safely  