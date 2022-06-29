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