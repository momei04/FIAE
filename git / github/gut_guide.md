# Git Guide

## Essential Commands

## First Steps
### Initializing a repository
this command creates (= initializes) a new repository in the current folder. <br>
Sets up the basic files and directories (r.g .git folder) needed to start tracking the changes <br>
`git init`


### cloning a Repository
- creates a copy of an existing repository on your local machine
- copies the entire history and specified repository on your local machine
  `git clone [repository URL]`
<hr>

## Tracking changes
### Adding files to the staging area
- adds a file to your staging area
- prepeares the changes for the next commit
- adds specified file or directory to the index (list of changes you want to commit)
`git add [file / directory]`


### commiting changes with a message
- creates a commit with a message describing the changes you added to your chnges list
- the message flag -m describes your changes
- takes a snapshot of your code and saves it on your local machine
`git commit -m "[commit message]"`

### Pull Changes
- updates a local repository
- pulling the changes from the remote repository and merging them with the local changes
`git pull`

### Push changes
- pushes the local commit to the repository
- updating the remote repository with the changes you made locally
<hr>

## Branching
### List brqanches
- lists all branches in the local repository
- a branch is a paralel version of your project
- shows the current branch with an *
`git branch`

### switching a branch
- switches to a specified branch
- updates the working directory to match the contents of the specified branch
`git checkout [branch name]`

### Merge branch
- merges the current Branch into the specified branch
- combinds the changes from both branch
- creates a new commit
`git merge [branch name]`

### Fetching changes
- downloads the changes
- updates your local repository
- does not merge with your local branch
`git fetch`
<hr>

## Listing / Logging
### Listing all commits
- shows a list of all commits in the repository
- displays author, date and commit message
`git log`

### List all remote repos
- list all the remote repositories associated with the local repository
- shows the url of each remote repository
`git remote -v`

### Check difference
- shows the difference between the working directory and the staging area (all added files)
- displays changes made to the specified line
`git diff [file]`

### CHeck status
- shows the current status of the local repository
- shows all staged (changes in commit list) and unstaged changes
  `git status`

### Checking the commit History
- shows the history of the commits you made
-
`git log`

