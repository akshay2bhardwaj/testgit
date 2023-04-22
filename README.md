<div align="center">
  <img src="https://git-scm.com/book/en/v2/images/lifecycle.png">
</div>

# Setup
## Version check
```
git -- version
```
## Setup Username
```
git config --global user.name "Akshay"
```
## Setup Email
```
git config --global user.email "akshay@github.com"
```
## List all configuration
```
git config --list
```

# Get start

## Initiate git repository if new project
```
git status
```
```
git init
```
## Remove project from git
```
rm -rf .git
```

## If new files created, move Untracked files to Staged file
```
git status
```
```
git add --a
```
or
```
git add FileNameMask
```
## Commit Staged files
```
git commit -m "description"
```
## Stage and Commit together
```
git commit -a -m "comment"
```
## To Clone from Server files
```
git clone link
```
```
git status
```
Do changes in Unmodified files (Commited files or Staged Files) then run
```
git status
```
result will be modified

## Stage modified files 
```
git add --a
```
## Commit Staged files
```
git commit -m "description"
```
# Restore
## Stage to Unstage or modified files
```
git restore --staged FileNameMask
```
or
```
git restore --staged .
```
## Restore modified files to Unmodified file from last commit
```
git restore FileNameMask
```
or
```
git restore .
```
## Restore Stage to Unmodified file from last commit
```
git restore .
```
or
```
git restore FileNameMask
```
## Check Log
```
git log
```
# .gitignore
## Add directory to .gitignore file which have to ignore

/dir/ - any specific repo\n
dir/ - all folder or file anywhere with name dir\n
FileNameMask - any file\n
/dir/FileNameMask - any specific file

## Move to Untracked files
```
git remove --cached FileName
```
# Diff
## after change before staged
git diff
## after change after staged
git diff --staged
# Branch
## To create new branch
```
git checkout -b devlope
```
## To switch
```
git checkout BranchName
```
## Current branch
```
git branch -v
```
## All merged branch
```
git branch--merged
```
## All Non merged Branch
```
git branch --no-merged
```
Delete Branch
```
git branch -d BranchName
```
## Merge any other branch to current working branch
```
git merge BranchName
```
# Remote
## Generate SSH Key
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
```
eval "$(ssh-agent -s)"
```
```
ssh-add ~/.ssh/id_ed25519
```
## Copy SSH Key to Clipboard
```
clip < ~/.ssh/id_ed25519.pub
```
Add SSH Key to Remote
## Add remote repository to origin
```
git remote add origin link
```
```
git remote
```
```
git remote -v
```
## Push to server
```
git push -u origin BranchName
```
## Pull from server
```
git pull origin BranchName
```
## Delete Branch from remote
```
git push origin -delete BranchName  
```
https://www.youtube.com/watch?v=evknSAkUIvs&list=PLu0W_9lII9agwhy658ZPA0MTStKUJTWPi
