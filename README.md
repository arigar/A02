# A02 

## Introduction

This tutorial explains how to use Git, Visual Studio Code (VS Code), and GitHub together to manage projects, track changes, and synchronize files between a local computer and a remote repository.

---

## Software Installation

Before starting, the following software must be installed:

• Git: https://git-scm.com/install/ 
• Visual Studio Code: https://code.visualstudio.com/download

---

## Git Configuration

After installing Git, it must be configured.

Open the terminal and run:

git config --global user.name "Your Name"  
git config --global user.email "youremail@example.com"

This step ensures commits are properly labeled.

---

## Cloning a Repository

To work on a GitHub project locally:

1. Open Visual Studio Code  
2. Open the Command Palette (Ctrl + Shift + P)  
3. Select **Git: Clone**  
4. Paste the repository URL  
5. Choose a local folder  
6. Open the cloned project

This creates a local copy of the project.

---

## Making Changes

Files inside the project can now be edited using VS Code.

For example:

• Open README.md  
• Modify the content  
• Save the file (Ctrl + S)

Git will automatically detect changes.

---

## Committing Changes

To save project updates:

1. Open the Source Control panel  
2. Review changed files  
3. Enter a commit message  
4. Click Commit

Commits represent saved snapshots of work.

---

## Pushing Changes

To upload updates to GitHub:

1. Click **Sync Changes**  
OR  
2. Run: git push

This sends commits to the remote repository.

---

## Pulling Updates

To download updates made remotely:

git pull

This synchronizes local files with GitHub.

---

## Fetching Updates

git fetch

Fetch retrieves changes without merging them.

---

## Branching and Merging

Branches allow parallel development.

• Create branch: git branch branch-name  
• Switch branch: git checkout branch-name  
• Merge branch: git merge branch-name

---

## Glossary

• **Branch** – A parallel version of a repository used for independent development  
• **Clone** – A copy of a repository stored locally  
• **Commit** – A saved snapshot of changes  
• **Fetch** – Retrieves updates without merging  
• **GIT** – A distributed version control system  
• **Github** – A platform for hosting repositories  
• **Merge** – Combines changes from different branches  
• **Merge Conflict** – Occurs when Git cannot automatically combine changes  
• **Push** – Uploads local commits to a remote repository  
• **Pull** – Downloads and merges remote changes  
• **Remote** – A version of the repository stored online  
• **Repository** – A project storage location tracked by Git

---

## References

• Git Documentation – https://git-scm.com/docs  
• GitHub Documentation – https://docs.github.com/  
• Visual Studio Code Documentation – https://code.visualstudio.com/docs
