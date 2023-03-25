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

## If New repository created 
```
git status
```
```
git init
```

## If new files created, to move file in Staged + Unmodified Untracked file
```
git status
```
```
git add --a
```
or
```
git add *FileName
```

## To Clone
```
git clone *link
```
```
git status
```
# Below operations same for both cloned files or created files
## Do changes in Unmodified files 
git status
result will be modified

## Stage modified files 
git add --a

git commit -m "description"
git log
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
 
