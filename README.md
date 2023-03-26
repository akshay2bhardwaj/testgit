<div align="center">
  <img src="https://git-scm.com/book/en/v2/images/lifecycle.png">
</div>

## Version check
```
git -- version
```
# Setup
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
## To Clone from Server commited files
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
# Undo
## Stage to Unstage specific file
```
git restore --staged FileName
```
## Stage to Unstage everything
```
git reset
```
## Restore modified files to Unmodified file from last commit
## Restore specific file
```
git checkout -- FileName
```
## Restore everything
```
git checkout -f
```
## Check Log
```
git log
```
# .gitignore
## Add all directory to .gitignore file which have to ignore
/dir/ - any specific repo\
dir/ - all folder anywhere with name dir
## Move to Untracked files
```
git remove --cached FileName
```
## Add all file to .gitignore file which have to ignore
Error.txt - any specific\
\*.txt - pattern
# Diff
## after change before staged
git diff
## after change after staged
git diff --staged
## Remote
```
git remote add origin git@github.com:akshay/folder
```
```
git push -u origin master
```
```
git pull origin master
```
git reset file
git checkout file 
git clone git@github.com:akshay/folder.git .

https://www.youtube.com/watch?v=evknSAkUIvs&list=PLu0W_9lII9agwhy658ZPA0MTStKUJTWPi
 
