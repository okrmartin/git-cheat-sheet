# Ignoring files

## update-index
This command is useful when you want to ignore changes in a commited file.
> git update-index --assume-unchanged path/to/file

The next command start tracking again the file
> git update-index --no-assume-unchanged path/to/file