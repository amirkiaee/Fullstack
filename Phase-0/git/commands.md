# Git Commands

This document contains the essential Git commands I learned in Phase 0.
Each command is explained briefly with its real purpose in daily development.

## 🔹 Repository Setup

### Create New git Repository

Initializes a new Git repository in the current folder.

`git init`

### Clone a Repository

Clones an existing repository from GitHub to the local machine.

`git clone <repository-url>`

## 🔹 Checking Repository State

### git Status

Shows the current state of the working directory and staging area.

`git status`

### git Difference

Shows differences between the current working directory and the last commit.

`git diff HEAD`

### Commits History

Displays the commit history of the repository.

`git log`

### Show Detailed (Commit or Tag)

Shows detailed information about a specific commit or tag.

`git show <commithash-or-tagName>`

## 🔹 Staging & Committing

### Add File to Stage

Adds files to the staging area.

- All files:
  `git add -A`

- a particular file:
  `git add <file-name>`

### Create Commit

Creates a commit with a descriptive message.

`git commit -m "commit message"`

### Create Commit and Sign it

Creates a signed commit using a GPG key.

`git commit -S -m "signed commit message"`

### Restore from Stage

Removes files from the staging area (without deleting them).

`git reset <file-name>`

## 🔹 Removing Files

### Remove File

Removes files from both the working directory and Git tracking.

`git rm <file-name>`

## 🔹 Branching

### Show all Branches

Lists all branches in the repository.

`git branch`
