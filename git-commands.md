# Basic Git commands

## Initialize a Git repository

> git init

## Add a remote repository

> git remote add origin [repository_url]

## Clone an existing repository

> git clone [repository_url]

## Create a new branch

> git checkout -b [branch_name]

## Switch to an existing branch

> git checkout [branch_name]

## Push a branch to the remote repository

> git push -u origin [branch_name]

## Check the status of the repository

> git status

## Add changes to the staging area

> git add [file_name] or git add .

## Commit changes 

> git commit -m "Commit message"

## Pull updates from the remote repository

> git pull origin [branch_name]

## Merge one branch into another

> git checkout [target_branch]
  git merge [source_branch]

## Delete a branch

> git branch -d [branch_name]
