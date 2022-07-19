# git

## git status
status of **local** git repo 

# branches

change the branch

`git checkout <branchname>`

create new branch

`git checkout -b <branchname>`

check all available branches

`git branch`

push branch into remote repo
`git push --set-upstream origin <branchname>`

after merging branch to master it's good practice to delete that branch.

delete the branch LOCALLY
`git branch -d <branchname>`

delete branch to the remote server
`git push origin --delete remoteBranchName`


git pull for rebase
`git pull -r`
pull everything from remote repo and add our commit at the top of the commits

Git Stash

stash our changes which we don't want to commit yet
`git stash`

get back changes
`git stash pop`

# History

we can go back to a specific project version

`git checkout <commithash>`

# Undoing and changing commits

reset last commit and changes aswell

`git reset --hard HEAD~1`

to keep the change in you working directory.
change still there but commit has gone

`git reset --soft HEAD~1`

reset last commit in remote repo
`git reset --hard HEAD~1`
`git push --force`
**NOTE** don't do this in master branch

revert commit

creates a new commit to revert the old commit's changes
`git revert <commithash>`

removes old commit
<<<<<<< HEAD
`git rest <commit hash>`

# Merging branches
=======

`git rest <commit hash>`
>>>>>>> 70f1427f77cf3b3a9898fb7336d5e744a27e88cc
