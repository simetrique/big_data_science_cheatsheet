# Linux commands

## Files and folders

Useful commands to operate with files and folders.

|Command|Description|
|---|---|
|pwd|Print current directory|
|ls|Show files and directories in current folder|


Print current directory:
```
pwd
```

Show files and directories in current folder:
```
ls

# Show files and directories as a list
ls -l

# how all including hidden files and folders
ls -la
```




Show files and directories as a list:
```
$ ls -l
drwx------@  5 admin  staff      160 Oct 29 11:54 Applications
drwx------+  7 admin  staff      224 Oct 29 09:54 Desktop
drwx------+ 25 admin  staff      800 Oct  7 17:48 Documents
drwx------+ 65 admin  staff     2080 Nov  4 15:02 Downloads
drwx------@ 75 admin  staff     2400 Oct 13 22:47 Dropbox
```
Show all including hidden files and folders:
```
$ ls -la
-rw-r--r--@  1 admin  staff      407 Sep 13 12:29 .bashrc
drwx------   2 admin  staff       64 Nov  4 18:15 .Trash
drwx------   7 admin  staff      224 Sep 19 13:31 .ssh
drwx------@  5 admin  staff      160 Oct 29 11:54 Applications
drwx------+  7 admin  staff      224 Oct 29 09:54 Desktop
drwx------+ 25 admin  staff      800 Oct  7 17:48 Documents
drwx------+ 65 admin  staff     2080 Nov  4 15:02 Downloads
drwx------@ 75 admin  staff     2400 Oct 13 22:47 Dropbox
```

Show size of all files and folders in human-readable format:
```
du -bsh *
```

## Editors


## Access rights


## Utilities



