# A Guide to Git using Command Line

### Keywords

+ Origin = remote branch

### Command Arguments

+ -u = Adds a tracking reference for git history
  + short for --set-upstream
+ -d = Delete
  + -D = force delete  

## Git Rename
---

### Local

1. Checkout the current branch:

`git checkout <old_branch_name`

2. Rename the local branch:

`git branch -m <new_branch_name>`

3. Branch has now been renamed

### Remote

1. Complete the steps for local renaming
   
2. Push the renamed branch to the origin

`git push origin -u <new_branch_name>`

3. Delete the old branch from remote

`git push origin -d <old_branch_name>`