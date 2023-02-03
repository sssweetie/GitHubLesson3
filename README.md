# GitHubLesson3

This is our first commit
We are using text for example

_**Add my Abstract about Git lessons.**_ 

## Here is it :D

## PowerShell
To create new file from terminal use

**new-item** item_name

## Always first

**git init** - Initializing git repository

**git status** - check status

## Git add

* **git add .** - Add all versions and differences of our files for commit
* **git add "file name"** - add the exact file.

## Git commit
* **git commit -m "message"** - fix changes and create a version of our files + Add some message
* **git log** - check out commit history, our branch, commit hash.
* **git commit -am "message"** - git add + git commit -m, by one line.
* **git checkout** - allow us to move between commit's by adding commit hash "35s8" in the end.
* **git checkout master** - get back to main tree(commit)
* **git diff** - let us see the exact changes in the file.

## Git branch

* **git branch** - show all branches available
* **git branch branch_name** - create new branch
* **git branch -d branch_name** - delete branch if it merged already
* **git branch -D branch_name** - force delete of the branch, even if it's not merged yet.
* **git log --graph** - show commit history with graphics.
* **git merge branch_name** - merging current branch with branch_name.
## GitHub work

* **git clone "URL from github project** - clone repository
* **git clone "URL from github project" "folder_name** - clone repository and create folder for it in the project.
* **git pull** - download commit with changes.
* **git push** - upload commit with changes.