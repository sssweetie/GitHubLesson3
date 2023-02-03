# GitHubLesson3

# List of commands

> [!IMPORTANT]
> Make sure you write everything correctly 

**git init** - initializing empty git repozitory

Инициализация пустого гит репозитория (если репозиторий уже инициализирован, повторно делать это действие не нужно)

**git status** - show untracked files

![Git status image](git status.png)

## git add - add version

* git add . - add version to all files

* git add file_name - add file version

## git commit - save changes

* git commit -m "message" - allow us to avoid git console and type massage inside terminal

* git commit -am "message" - the same as flag -m but allow us to avoid git add

## git log  - get story of commits

 - git log --graph - get story of commits in a graphic way

## git checkout - switch between commits

- git checkout master - get back to main tree

- git checkout branch_name - switch to the branch

> [!IMPORTANT] 
> Write four first numbers of commit after checkout

**git diff** - show the differences between current state and last commit

## git branch

* git branch - show where I am (what branch)

* git branch branch_name - create a new branch

* git branch -d branch_name - delete merged branch

* git branch -D branch_name - force deleting branch
