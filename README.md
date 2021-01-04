# Coding with Beng - Git/Github

Tutorial video: https://www.youtube.com/watch?v=FR221ALdCUA&ab_channel=CodingwithBeng

## Git Commands

`git init` : creates a new .git folder in the current directory to make it a git repository

`git diff` : shows all changes to all files in repository since last commit

`git add .` : adds all files to staging bucket

`git commit -m "<insert message>"` : creates a new commit in repository with all changes in staging bucket

`git push` : pushes commmits to Github (or other remote repository that you have connected)

`git checkout -b <branch name>` : creates a new branch off which will be a copy of the current branch

`git branch` : lists out all branches for repository

`git checkout <branch name>` : switches to another existing branch


`git pull` : copies down all commits from remote repository to your local repository (your computer)

`git rebase origin/master` : rebases your branch off of the master branch so that it now has all the newest commits

`git push -f` : must be done after a rebase (and after you have resolved conflicts) to add changes to remote repository

`git merge -m "<insert message>" <branch name>` : merge commits in a specified branch into the current branch and attaches a message to that merge. This is similar to when you click the "merge branch" button in Github on a Pull Request

`git reset --hard <commit id>` : rewinds repository back to a specific commit id (and removes all commits that happen later than the specified commit)

## Terminal Commands

`pwd` : "print working directory", prints out the current folder/directory that you are in

`ls` : "list", lists out files in current directory

`cd` : "change directory", moves to another directory
