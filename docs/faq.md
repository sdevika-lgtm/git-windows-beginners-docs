# Frequently Asked Questions
## Table of Contents
- [What is Git Bash?](#what-is-git-bash)
- [Where should I run Git commands?](#where-should-i-run-git-commands)
- [Why doesn't the `pwd` command work in Command Prompt?](#why-doesnt-the-pwd-command-work-in-command-prompt)
- [Why can't I find my Desktop folder using `ls`?](#why-cant-i-find-my-desktop-folder-using-ls)
- [What is a Git repository?](#what-is-a-git-repository)
- [What is the staging area in Git?](#what-is-the-staging-area-in-git)
- [What is the difference between Git and GitHub?](#what-is-the-difference-between-git-and-github)
- [What is a README file?](#what-is-a-readme-file)
### What is Git Bash?
Git Bash is a terminal application that allows you to run Git commands on a Windows system.

It provides a command-line interface where you can type and execute Git commands such as `git init`, `git add`, and `git commit`.

Unlike Command Prompt, Git Bash supports Unix-style commands like `ls`, `pwd`, and `cd`, which are commonly used in Git tutorials.
### Where should I run Git commands?
Git commands should be run inside Git Bash.

After installing Git, open Git Bash and type commands in the terminal window.

Commands such as `git init`, `git status`, and `git commit` will not work correctly in Command Prompt if Git is not configured for it.
### Why doesn't the `pwd` command work in Command Prompt?
The `pwd` command is a Unix-style command and is not supported in Windows Command Prompt.

It works in Git Bash because Git Bash provides a Unix-like environment.

If you are using Command Prompt, use `cd` to check your current directory instead.
### Why can't I find my Desktop folder using `ls`?
On some Windows systems, the Desktop folder may be located inside the OneDrive directory.

If `ls` does not show a `Desktop` folder, try navigating to:
```bash
cd ~/OneDrive/Desktop
```
You can also use the `ls` command to explore available folders and locate the correct path.
### What is a Git repository?
A Git repository is a folder that Git tracks to manage changes in files.

When you run `git init`, Git creates a hidden `.git` folder that stores version history and tracking information.

This allows you to save changes, track versions, and manage your project over time.
### What is the staging area in Git?
The staging area is a place where you prepare files before saving them as a commit.

When you run `git add`, files are moved to the staging area.

When you run `git commit`, the staged files are saved as a new version.
### What is the difference between Git and GitHub?

Git is a version control system used to track changes in files on your local machine.

GitHub is a platform that hosts Git repositories online, allowing you to store, share, and collaborate on projects.
### What is a README file?
A README file is a Markdown document that provides an overview of a project.

It typically includes information about the purpose of the project, how to use it, and what files are included.

On GitHub, the README file is displayed as the main page of the repository.
