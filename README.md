# Git documentation
## Is a file to implement to help newbies to learn basic Git commands

### .gitignore
in order to ignore a folder in your .gitignore file, write the name of the folder followed by à "/".  
```folder/```

### Staging
```
git add <file_name>
```
for specific files or 
```
git add .
```
for all

### Commiting
```
git commit -m "<your_message>"
```

### Push
view origin
```
git remote show origin <your_branch>
```
change remote origin
```
git remote set-url origin <your_new_remote>
```
actual push command
```
git push origin <your_branch>
```

### Pull
```
git pull origin <your_branch>
```
in case of conflicts, use staging / commit (explained before) or stashing
```
git stash
```
then pull
```
do the pull above
```
then pop stash to resolve code from incoming code vs working directory code
```
git stash pop
```

### Merge
go to destination branch
```
git checkout <your_branch>
```
and merge from the branch you want
```
git merge <origin_branch>
```
