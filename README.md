# sandbox
This is a sandbox repository for playing with git. 

# Git cheatsheet
## Installing git
To install git on your machine visit - https://git-scm.com/downloads and select the platform of your choice.

## Configuration
**$ git config --global user.name "\[name\]"**

> Sets the name you want attached to your commit transactions

**$ git config --global user.email "\[email\]"**

> Sets the email you want attached to your commit transactions

**$ git config --global color.ui auto**

> Enables helpful colorization of command line output

## Create Repository
Start a new repository or obtain one from an existing URL 

**$ git init \[project-name\]**

> Creates a new local repository with the specified project-name

**$ git clone \[url\]**

> Create a local copy of a remote repository

## Make Changes
Review and commit changes

**$ git status**

> Lists all changes \(new as well as modified\)

**$ git diff**

> Show differences in files, that have not been staged, with last comitted version.

**$ git add [file]**

> Stages the file specified for commit

**$ git reset [file]**

> Unstages the file specified

**$ git commit -m \"[decriptive message]\"**

> Records the changes permanently in version history.

## Branching and merging

**$ git branch**

> List all local branches in the current repository


**$ git branch \[branch-name\]**

> Creates a new branch with specified name

**$ git checkout \[branch-name\]**

> Switches the working directory to the specified branch

**$ git merge \[branch-name\]**

> Combines the specified branch\'s history into the current working directory

**$ git branch -d \[branch-name\]**

> Deletes the specified branch







