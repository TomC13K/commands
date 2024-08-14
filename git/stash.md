# Git stash commands

https://www.youtube.com/watch?v=BSLzA8oCT7g

```bash
# need to add the changes first (only tracked files)
git add .
git status
git stash             # stash all changed files

# or name the stash
git stash -m "My stash name"

# check my stashes
git stash list          # show indexes of the stashes

# pick specific stash index(1) to add to branch
git stash pop --index 1

# show files stashed
git stash show

# git status to see no changes n default state of the branch
git status

# ===============================
# apply stashed files back
# in case there is multiple shashed changes the latest is used
git stash pop

# clear all stashes
git stash clear


# ===============================
# create new branch from the specified stash on index(1)
# it will automatically change my working branch to that new one
git stash branch <branchNAME> 1
```