# Git commands


### Remove file / folder from being tracked
- after push to origin and check if correct

```bash
git rm -r --cached src/main/<path_to_file>

# wasnt working on folder
git rm --cached file

# other way 
git stash
git rm -rf --cached .
git add .

# remove the specific file - sometimes still doesnt work
git rm --cached <file path... sites/default/settings.txt>

```

