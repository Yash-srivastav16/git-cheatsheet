# Git-Cheat Sheet
Git-Cheat Sheet

## Creating and Cloning Repositories</br>
**git init:** Initialize a new Git repository in the current directory.</br>
**git clone <repository URL>:** Clone a remote repository to your local machine.</br>

## Basic Commands</br>
**git add <file>:** Stage changes to a file for committing.</br>
**git commit -m "message":** Commit staged changes with a descriptive message.</br>
**git status:** Show the current status of the repository, including any changes that have been made.</br>
**git log:** Show a log of all commits in the repository, including the commit message and author.</br>

## Branching and Merging</br>
**git branch:** List all branches in the repository.</br>
**git checkout <branch>:** Switch to a different branch.</br>
**git merge <branch>:** Merge changes from a branch into the current branch.</br>

## Working with Remote Repositories</br>
**git remote add <name> <repository URL>:** Add a remote repository to the repository.</br>
**git push <remote> <branch>:** Push committed changes to a remote repository.</br>
**git pull <remote> <branch>:** Pull changes from a remote repository to your local repository.</br>

## Undoing Changes</br>
**git reset:** Unstage changes that have been added.</br>
**git revert <commit>:** Revert a commit and create a new commit with the changes undone.</br>
**git checkout -- <file>:** Discard changes to a file that have not been staged.!</br>
