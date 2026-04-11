# Quick Start Guide
## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Steps](#steps)
- [Expected Outcome](#expected-outcome)
## Overview
This guide helps beginners set up git on Windows and create their first local repository.
## Prerequisites
- Windows System
- Git Installed
- Visual Studio Code Installed
## Steps
### 1. Install Git
Download and install git from the official website: 
[Download Git for Windows](https://git-scm.com/install/windows)

Run the installer and follow the default setup options.
### 2. Open Git Bash
To run the git commands, open Git Bash.

1. Press the **Windows** key on your keyboard.
2. Type **Git Bash** in the search bar.
3. Click open the **Git Bash** application from the search results.

A terminal window will open. This is where you will enter the git commands. 
### 3. Configure Git
In Git Bash, run the following commands to set your username and email address:
```bash
git config --global user.name "your-username"
git config --global user.email "your-email@example.com"
```
Your details tell git that you are the author of each commit.
#### 4. Navigate to your working folder
In Git Bash, use the `cd` command to move to the folder where you want to create your project.

To move to your Desktop, run:
```bash
cd ~/Desktop
```
On some systems, the Desktop maybe in the OneDrive folder. 

If the above command doesn't work, try:
```bash
cd ~/OneDrive/Desktop
```
Use `ls` to list the folders and confirm the path.
### 5. Create a project folder
Create a new folder and move into it:
```bash
mkdir my-first-project
cd my-first-project
```
You are now inside your project folder. 
### 6. Initialize a Git repository
For git to start tracking in the current folder, use:
```bash
git init
```
This creates a new git repository in your project.
### 7. Create your first file
Create a Markdown file inside the project folder:
```bash
touch README.md
```
To confirm the file was created, run:
```bash
ls
```
You should see README.md in the list. 
### 8. Stage and commit your file
Add the file to the staging area and save (commit) your first version:
```bash
git add README.md
git commit -m "First Commit"
```
To verify, run:
```bash
git status
```
You should see a message indicating that the working tree is clean. 
## Expected Outcome
By the end of this guide, you will:
- Have git installed in your Windows system
- Have git configured with your username and email
- Know how to use Git Bash to run commands
- Have created your first git repository
- Have successfully committed your first file
