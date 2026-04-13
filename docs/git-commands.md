# Git Commands Explained
## Table of Contents
## 1. Basic Workflow
### a. `git init`
#### Description
Initializes a new Git repository in the current folder.
#### Command
```bash
git init
```
#### Example Output
![Git Init Output](images/git-init-output.png)
#### Explanation
- Creates a new Git repository
- Generates a hidden `.git` folder
- Enables version control for the project
#### When to Use
Use this command when starting a new project that you want Git to track.
### b. `git status`
#### Description
Shows the current state of the repository.
#### Command
```bash
git status
```
#### Example Output
![Git Status](images/git-status.png)
#### Explanation
This output shows that Git has detected new files and folders that are not yet being tracked.

In this example:

- `docs/git-commands.md` is a new Markdown file
- `docs/images/` is a new folder
- these items are currently untracked
- they must be added with `git add` before they can be committed
#### When to Use
Use this command to check whether your repository has untracked, modified, or staged files before committing changes.
### c. `git add`
#### Description
Adds files to the staging area.
#### Command
```bash
git add .
```
#### Example Output
#### Explanation
- Moves files from untracked to staged
- Prepares files for committing
- The staging area holds changes before they are saved permanently
#### When to Use
Use this command after creating or modifying files to prepare them for a commit.
### d. `git commit`
#### Description
#### Command
#### Example Output
#### Explanation
#### When to Use