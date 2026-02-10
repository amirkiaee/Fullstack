# Git Commands

This document contains the essential Git commands I learned in Phase 0.
Each command is explained briefly with its real purpose in daily development.

## 🔹 Repository Setup

### git init

Initializes a new Git repository in the current folder.

`git init`

### git clone

Clones an existing repository from GitHub to the local machine.

`git clone <repository-url>`

## 🔹 Checking Repository State

### git status

Shows the current state of the working directory and staging area.

`git status`

### git diff head

Shows differences between the current working directory and the last commit.

`git diff HEAD`

### git log

Displays the commit history of the repository.

`git log`

### git show

Shows detailed information about a specific commit or tag.

`git show <commithash-or-tagName>`

## 🔹 Staging & Committing

### git add

Adds files to the staging area.

- All files:
  `git add -A`

- a particular file:
  `git add <file-name>`

### git commit

Creates a commit with a descriptive message.

`git commit -m "commit message"`

### git commit and sign

Creates a signed commit using a GPG key.

`git commit -S -m "signed commit message"`

### git reset

Removes files from the staging area (without deleting them).

`git reset <file-name>`

## 🔹 Removing Files

### git rm

Removes files from both the working directory and Git tracking.

`git rm <file-name>`

## 🔹 Branching

### git branch

Lists all branches in the repository.

`git branch`
