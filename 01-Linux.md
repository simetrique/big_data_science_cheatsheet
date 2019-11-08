# Linux commands

## Files and folders

General commands:

|Command|Description|
|---|---|
|`pwd`|Print current directory|
|`ls`|Show files and directories in current folder|
|`ls -l`|Show files and directories as a list|
|`ls -la`|Show all including hidden files and folders|
|`cd /abc`|Change directory, go inside /abc|
|`cd ..`|Go one level up|

CRUD:

|Command|Description|
|`touch myfile.txt`| Create file `myfile.txt`|
|`cp file.txt ~/docs`| Copy `file.txt` to directory `~/docs`|
|`cp -R dir1 dir2`| Copy (recursively) directory `dir1` to `dir2`|
|`mv file1 file2`| Rename file from `file1` to `file2`|
|`mv file ~/dir`| Move file to directory|
|`rm file.txt`| Remove file|
|`rm -r dir1`| Remove directory|

Preview files:

|Command|Description|
|`cat file.txt`| Print full content of the file|
|`head file.txt`| Print first 10 lines of the file|
|`head -n100 file.txt`| Print first 100 lines|
|`tail file.txt` or `tail -n100`| Print last 10/100 lines of file|
|`less file.txt`| Open file in preview mode|


Show size of all files and folders in human-readable format:
```
du -bsh *
```

## Editors


## Permissions


## Utilities



