# GitHubLesson3


## Welcome to [MarkDown]!
## Come to start...
### About of design text...

* to add a heading to the text, you must put the "#" sign. 

* to italicize text, you need to frame it with "*". *For example*

* to make the text bold, you need to frame it with "**". **For example**

* to make the text crossed out, you need to frame it with the sign "~~". ~~For exaple~~

to add unordered lists, you need to highlight the items by (*). For example:
* Element 1
* Element 2
* ...

to add numbered lists, you need to number the items. For example:
1. Element 1
2. Element 2

* To insert a picture, sound or another objects you need to write a structure - ! [] () (without spaces)

## Works with a repository

1. **git init** - initializing empty repozitory

2. **git status** - show untracked files

3. ### *_git add_* - add file version
* * * [!TIP]: **git add .** - add version to all files
* * * *        AND **git add --all

4. **git commit** - save changes

5. **git commit -m "message"** - allow us to avoid git console and type message incide terminal

~~this was supposed to be my ad~~

6. **git commit -am "message"** - the same as flag -m allow us avoid git add

7. **git log** - get story of commits
* * **git log --graph** - show change history graphically

8. **git checkout** - allow us switch commits

9. **git checkout master** - get back to main tree

10. **git diff** - show differences between current state and last commit

## Work with "branch"-es
* **git branch** - show all branches
* **git checkout <name_branch>** - allow to switch between branches
* * If you have no any branches, you must to whrite command **git branch <new_name_branch>**
* **git merge branch <name_branch>** - allow to add changes to current banch from <name_branch>

### And then ...
* **git branch -d <name_branch>** - delete <name_branch> (if <name_branch> was merge earlier)
* * **git branch -D <name_branch>** - delete <name_branch> ignoring whether there was a merge or not

## Works with a remote repository

### To start...
* To authorize:
* * • git config --global user.name "Your_name_only_english_language"
* * • git config --global user.email your_male@example.com

## Now we start working ...
* __git clone__ - this command allows you to transfer the remote repository to your computer
* * if you need to make changes to someone else's repository, then you need to use the **fork** command to make someone else's repository yours, then use the **git clone** command to create a local repository 
* * * [!Warning]: You must create NEW branch for job and working only in them!
* Then you work with repository by using command (see above)
* **git pull** - this command allows you to add information from a remote repository to the current local one, while simultaneously executing the command *merge*

### After working ...
* **git push** - this command allows you to push changes from the current local repository to a remote one
* * [!Warning]: You are must to be authorized into the system "Git" and "GitHub" (or other cloud of repository)
* * * If you work with else's repository, please: commit your changes in branch for push in your "copy-clone" fork, then you allowded to do *pull request*