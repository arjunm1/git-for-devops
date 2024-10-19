
# Git Command Overview

This document categorizes Git commands by different topics to help understand their usage. Each category includes a short description and the relevant Git command.

## 1. Initialization

Git commands for initializing repositories.

- **Initialize a Git repository**: Creates a new Git repository in the current directory.
  - Command: `git init`

## 2. Configuration

Git commands for setting up your identity and email, which are necessary for commits.

- **Set global username**: Set the global username used in commits.
  - Command: `git config --global user.name "Your Name"`

- **Set global email**: Set the global email used in commits.
  - Command: `git config --global user.email "youremail@example.com"`

## 3. File Operations

Commands to add, remove, and restore files in the Git repository.

- **Add files to the staging area**: Adds files to the staging area, marking them for commit.
  - Command: `git add <file>`

- **Remove files from the staging area**: Removes files from the Git index (staging area) without deleting them from your working directory.
  - Command: `git rm --cached <file>`

- **Restore files**: Restores file changes from the staging area or working directory.
  - Command: `git restore <file>`

## 4. Commit Changes

Commands for committing changes to the Git repository.

- **Commit changes**: Records the changes from the staging area to the repository.
  - Command: `git commit -m "Commit message"`

## 5. Branching

Commands to create, switch, and manage branches.

- **Create a new branch**: Creates a new branch from the current HEAD.
  - Command: `git checkout -b <branch_name>`

- **Switch branches**: Switches to another branch.
  - Command: `git checkout <branch_name>` or `git switch <branch_name>`

- **List branches**: Lists all the branches in the repository.
  - Command: `git branch`

## 6. Status and Logs

Commands to check the current state of the repository and view the commit history.

- **Check repository status**: Shows the current state of the working directory and staging area.
  - Command: `git status`

- **View commit history**: Displays a log of previous commits.
  - Command: `git log`

- **View commit history in one line**: Displays a simplified one-line log of commits.
  - Command: `git log --oneline`

## 7. Staging and Working Directory Management

Commands to stash changes when switching branches.

- **Stash changes**: Stashes uncommitted changes in a temporary location.
  - Command: `git stash`

- **Apply stashed changes**: Re-applies the latest stashed changes to the working directory.
  - Command: `git stash pop`

## 8. Branch Management

Commands for handling multiple branches during development.

- **Merge branches**: Combines changes from one branch into another.
  - Command: `git merge <branch_name>`

- **Rebase branches**: Reapplies commits from the current branch onto another branch.
  - Command: `git rebase <branch_name>`

## 9. File Inspection

Commands to inspect files and commits.

- **Show file content**: Shows the content of a file at a particular commit.
  - Command: `git show <commit_id>:<file_path>`

- **Check differences between changes**: Displays the changes between commits, branches, or files.
  - Command: `git diff`

## 10. Miscellaneous

Other helpful Git commands.

- **List files in the working directory**: Shows the files in the current directory.
  - Command: `ls`

- **Create a directory**: Creates a new directory.
  - Command: `mkdir <directory_name>`
