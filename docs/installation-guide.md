# Installation Guide
## Table of Contents
- [Overview](#overview) 
- [Download Git](#download-git)
- [Run the Installer](#run-the-installer)
- [Installation Options](#installation-options)
- [Complete Installation](#complete-installation)
- [Verify Installation](#verify-installation)
## Overview
This guide explains how to install Git on a Windows system and highlights the important options during setup.
## Download Git
Download Git for Windows from the official website:
[Download Git for Windows](https://git-scm.com/install/windows)
## Run the Installer
After downloading, locate the installer file (usually in your Downloads folder) and double-click it to start the installation.

Follow the on-screen instructions to proceed through the setup.
## Installation Options
During installation, you will see several configuration screens. For beginners, the default options are recommended unless specified otherwise below.

Below are some important options you may encounter:
### Choosing the Default Editor
Select **Visual Studio Code** if it is installed. This allows Git to use VS Code when editing commit messages.
### Adjusting the PATH Environment
Choose the recommended option that allows Git to be used from the command line.
### Choosing HTTPS Transport Backend
Select the default option (usually OpenSSL).
### Configuring Line Ending Conversions
Select the recommended option:
- Checkout Windows-style, commit Unix-style line endings
## Complete Installation
Continue through the remaining steps and click **Install**.

Once the installation is complete, click **Finish**.
## Verify Installation
Open Git Bash and run:
```bash
git --version
```
You should see the installed Git version displayed in the terminal:
`git version 2.xx.x`


