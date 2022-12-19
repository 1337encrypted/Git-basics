# Git basic initial commands

## Create a git repository

`git init`

## Clone a repo from github

`git clone`

## setting up name and email global, remove global to make it local

`git config --global user.name <name>`
`git config --global user.email <email@example.com>`

## Check status

`git status`

## Add files to the staging area

`git add .`   # All files
`git add -u`	# recently modified files

## Commit files

`git commit -m <description>`

# Traversing git history

`git log`

# -u is all the changes made in the repo

`git push -u origin main`

# merge the fetch as fetch wont be merged

`git merge origin main`

# fetch and integrate into the local repository

`git pull origin main`


# Git push

`git push <remote locl_branch>:<remote_branch>`

