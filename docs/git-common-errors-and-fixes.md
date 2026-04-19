# Git Common Errors and How to Fix Them
A beginner's guide to understanding how to fix error while using git commands.
## Table of Contents
1. [git not recognized](#git-not-recognized)
2. [nothing to commit](#nothing-to-commit)
3. [untracked files](#untracked-files)
4. [merge conflict](#merge-conflict)
5. [invalid branch name](#invalid-branch-name)
6. [command not found](#command-not-found)
7. [lost changes after restore](#lost-changes-after-restore)
8. [revert blocked by local changes](#revert-blocked-by-local-changes)
9. [editor waiting issue](#editor-waiting-issue)
## git not recognized
### a. Error
```bash
git is not recognized as an internal or external command.
```
### b. Why it happens
Git is not installed or not added to PATH.
### c. Fix
```bash
git --version
```
If not found:
- Install Git
- Restart terminal
## nothing to commit
### a. Error
```bash
nothing to commit, working tree clean.
```
### b. Why it happens
No changes were made or all changes are already committed.
### c. Fix
- Modify a file
- Save it
- Run:
```bash
git status
```
## untracked files
### a. Error
```bash
Untracked files:
```
### b. Why it happens
Git sees new files but they are not added.
### c. Fix
```bash
git add .
git commit -m "Add new files"
```
## merge conflict
### a. Error
```bash
CONFLICT (content): Merge conflict in file
```
### b. Why it happens
Two versions of the same file conflict.
### c. Fix
Resolve conflicts in VS Code using Merge Editor before committing.
```bash
git add .
git commit -m "Resolved merge conflict"
```
## invalid branch name
### a. Error
```bash
fatal: not a valid object name: 'String'
```
### b. Why it happens
Used a space in branch name.
### c. Fix
```bash
git branch feature-1
```
## command not found
### a. Error
```bash
command not found
```
### b. Why it happens
Command copied with hidden characters or typed incorrectly.
### c. Fix
- Retype command manually
- Avoid copy-paste from formatted sources
## lost changes after `restore`
### a. Error
File content lost  after using `git restore`
### b. Why it happens
Changes were not saved in the editor before restore.
### c. Fix
Always save the changes before running `git restore`

Use
```bash
ctrl+Z
```
to restore file contents
## `revert` blocked by local changes
### a. Error
Your local changes would be overwritten
### b. Why it happens
Uncommitted changes conflict with revert.
### c. Fix
Use
```bash
git stash
git revert HEAD
git stash pop
```
## editor waiting issue
### a. Error
Waiting for your editor to close the file
### b. Why it happens
Git opened editor for commit message.
### c. Fix
- Save file (ctrl+S)
- Close the editor tab
> Related guide: [Git Commands Explained](git-commands.md)