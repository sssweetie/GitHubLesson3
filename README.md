# Basic git commands

## Create git repository

**git init** - this command creates empty git tepository or reinitialize an existing one

## Recording changes to the repository

### 1. Checking the status of file  
* **git status** - This command we use to determine which files are in which state.

### 2. Tracking new file  
* **git add \<name file>** - We use this command to begin tracking new file (files) 
* **git add .** - This command to begin tracking all files

### 3. Committing changes
* **git commit** - We use this command when we are ready to save changes 
* **git commit -m 'message'** - This command allow us to avoid git console and type message inside terminal 
* **git commit -am 'message'** - This commmand the same as flag -m but allow as to avoid git add 

## Viewing the commit history and detailed changes 

**git log** - Show the history of commits. The output is given in reverse chronological order by default.
* **git log --graph** - Show the history of commits in graphic view

**git giff** - Show changes between current state and last commit

## Swith between commits and branches

* **git checkout** - This command use to swith between commits

* **git checkout master (main)** - This command use to get back to master (main) tree

## Work with branches and merges 

### 1. Basic branching
* **git branch** - show the list of branches 

* **git branch branch_name** - create a new branch with name "branch_name"

* **git branch -d branch_name** - delete merged branch 

* **git branch -D branch_name** - force deleting branch

### 2. Basic merging

* **git merge branch_name** - merging branch_name with current branch