<div align="center">
  <img src="https://git-scm.com/book/en/v2/images/lifecycle.png">
</div>

# Version check
```
git -- version
```
## Setup
# Setup Username
```
git config --global user.name "Akshay"
```
# Setup Email
```
git config --global user.email "akshay@github.com"
```
# List all configuration
```
git config --list
```

--> Get start

-->If New repository created 
git status
git init

--> If new files created, to stage untracked file in case of New file created 

git status
git add --a
or
git add file

-->if clone

git clone link
git status


-->Do changes
git status
result - Modified

--> Stage
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
 
