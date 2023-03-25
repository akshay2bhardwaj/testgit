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

## Initiate git repository
```
git status
```
```
git init
```

## If new files created, to move Untracked files in Staged file
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
# Below operations same for both cloned files or created files
## Do changes in Unmodified files (Commited files)
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
## Check Log
```
git log
```
# .gitignore
## Add all directory to .gitignore file which have to ignore
/dir/ - any specific repo\n
dir/ - all folder anywhere with name dir
## Add all file to .gitignore file which have to ignore
Error.txt - any specific
\*.txt - pattern
## Remote
git remote add origin git@github.com:akshay/folder
git push -u origin master
git pull origin master

after change before staged
git diff file

after change after staged
git add file
git diff --staged file
git reset file
git checkout file 

git clone git@github.com:akshay/folder.git .

https://www.youtube.com/watch?v=evknSAkUIvs&list=PLu0W_9lII9agwhy658ZPA0MTStKUJTWPi
 
