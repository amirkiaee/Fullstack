# Terminal Commands (Linux / Git Bash)

## 🔹 Navigation

### Show Working Path

reports the working directory path

`pwd`

### Show Files List

lists files and directories in the current directory

- default:
  `ls`
- show hidden files:
  `ls -a`
- show detailed files:
  `ls -l`
- hidden + detailed:
  `ls -la`

### Change Directory

change the working directory

`cd <directory-name>`

- get back:

`cd ..`

- get home:

`cd ~`

## 🔹 Creation

### Make Directory

create one or more directories specified by the Directory parameter

- one directory:

`mkdir <directory-name>`

- multiple nested directories:

`mkdir -p <external-directory>/<internal-directory>`

### Make Empty File

create an empty file

- one file:

`touch <file-name.format>`

- multiple files:

`touch <first-file-name.format> <second-file-name.format> ...`

## 🔹 Manipulation

### Copy

copy files and directories

- files:

`cp <original.format> <copy.format>`

- directories:

`cp -r <original-directory> <copy-directory>`

### Move

move files and directories from one directory to another or to rename a file or directory

- rename file:

`mv <old-name.format> <new-name.format>`

- move files:

`mv <file-name.format> <path>`

### Remove

remove files or directories you no longer need

- files:

`rm <file-name.format>`

- directories:

`rm -rf <folder-name>`

⚠️ This command permanently deletes files and folders without confirmation.

## 🔹 Concepts

### Path

- current directory:

`.`

- parent directory:

`..`

- home:

`~`

## 🔹 Utilities

### Clear Terminal

clears your screen, if possible

`clear`

### Read Files (small size)

reads each File parameter in sequence

`cat <file-name.format>`

### Read Files (large size)

reads each File parameter in sequence

`less <file-name.format>`

### Fast Open VS Code

open visual studio code in this directory

`code .`

### Nano Text Editor

open internal text editor

`nano <file-name.format>`
