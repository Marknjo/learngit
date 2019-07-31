# Introduction to GitHub and Git Basic Syntax

Simple Guideline on how to use git bash.

## Basic Git Commands

### Setting Up Git

- git init
  Initializes a git repo.
- git push remote origin < url >  
  Adds local repository to the remote one.  

- git push -u origin master

  Pushes the local created repo to remote (Github)

- git push origin master

 Updates the remote's master branch with with local repo.

### Basic Checks of Status Adding Files to Git and Commiting Them

- git status
  
  Checkes the git status of the files.

- git add < filename >
  
  Adds files to the staging area

- git commit -m  "Your descriptive message"
  
  Commits the changes to the repository.

### Dealing With Master Origin and Branches

- git log

 Checks the log status

- git branch -b < Branch-name >
  
  Creates a new branch and switch to it.

- git checkout master

 Moves the header from the current branch to the master branch

- git merge < branch-name >
  
  First you have to move the header to the branch you want to merge to. i.e. Checkout to master then, merge the branch name to master.
