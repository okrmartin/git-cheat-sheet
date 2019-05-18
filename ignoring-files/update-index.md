# Ignoring files
Usually a file can be ignored if it is added to the .ignore file or to the 
.git/info/exclude file, witch is an untracked file by default.

## update-index
This command is useful when you want to ignore changes in a commited file.
```
git update-index --assume-unchanged path/to/file
```

The next command start tracking again the file
```
git update-index --no-assume-unchanged path/to/file
```