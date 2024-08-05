# git diff  

## Add this to the .git/config file
git config diff.tool vimdiff

# show diff between tracked files in the working and staging area
` git diff`

# show diff between staging area and most recent commit, in short shows what we are about to commit
`git diff --staged`

## diff info with previous commit
`git diff HEAD HEAD^1 -- filename`

## Use difftool
`git difftool HEAD HEAD^1 -- filename`

## how to show what changed with each commit
`git log -p`
