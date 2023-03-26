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

## If new files created, move Untracked files to Staged file
```
git status
```
```
git add --a
```
or
```
git add FileName
```
## Commit Staged files
```
git commit -m "description"
```
## To Clone from Server commited+Pushed files
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
## Stage to Unstage specific file
```
git restore --staged FileNameMask
```
or
```
git restore --staged .
```
## Restore modified files to Unmodified file from last commit
## Restore specific file
```
git restore FileNameMask
```
or
```
git restore .
```
## Restore Stage to Unstage specific file Unmodified file from last commit
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
/dir/ - any specific repo\
dir/ - all folder anywhere with name dir
## Add file to .gitignore file which have to ignore
Error.txt - any specific\
\*.txt - pattern
## Move to Untracked files
```
git remove --cached FileName
```
# Diff
## after change before staged
git diff
## after change after staged
git diff --staged
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
## Add SSH Key to Github
```
clip < ~/.ssh/id_ed25519.pub
```
Add repository to Github
```
git remote add origin link
```
```
git remote
```
```
git remote -v
```
```
git push -u origin master
```
```
git pull origin master
```
https://www.youtube.com/watch?v=evknSAkUIvs&list=PLu0W_9lII9agwhy658ZPA0MTStKUJTWPi
