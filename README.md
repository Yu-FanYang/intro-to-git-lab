# intro-to-git-lab
This repository is for the version control lab assignment

## Author: Yu-Fan Yang
*My favorite programming language is Python. It allows both interactive mode and script mode that are useful for beginners and professionals.**

## Project Overview
The purpose of CheckPoint 1 is to introduce students to version control, Git fundamentals, and GitHub for collaboration and project managment.
### Key Learning Outcomes:
- Understand the concept and purpose of version control.
- Learn basic Git commands.
- Create and manage GitHub repository.
- Write a well-structured README file using Markdown.
- Collaborate using GitHub features like pull requests and issue tracking.

## Key Concepts:

### Definition of version control:
Version control for Git is a way to track changes to files over time. It is useful in software development especially work in groups that each member work on the same codebase. It allows the members to track revision history and rollback capabilities. Developers can also create braches to work on the projects and then merge the code into main code.

### Importance of Version Control
- Track Changes: Maintains a history of edits, additions, and deletions for easy reference.
- Facilitates Collaboration: Enables multiple developers to work on a project without conflicts.
- Ensures Backup & Recovery: Provides a safety net to revert to previous versions if needed.
- Resolves Conflicts: Helps manage simultaneous changes by different contributors.
- Supports Auditing & Accountability: Keeps a record of who made changes and when.

### Key Features of Git
- Distributed Architecture: Each user has a full copy of the repository, allowing offline work and eliminating single points of failure.
- Branching & Merging: Enables developers to work independently on different features and merge changes seamlessly.
- Data integrity: Uses cryptographic hashing to protect data from corruption.
- High Performance: Optimized for speed and efficiency, even with large repositories.

## How to Run This Project:
### 1.Clone Repository
- Open a terminal or command prompt.
- Navigate to directory where you want to store the repository.
- Run the command `git clone <repository_URL>`
* Replace _<repository_URL>_ with the actual repository link

### 2.Navigate to the Cloned Repository
- Use the command `cd <reposotory_name>`.
- Replace _<reposotory_name>_ with the cloned repository folder name.

### 3.View the Content
- List files using `ls` on Linux and `dir` on Windows.
- Open files using an editor or view them directly from terminal.


### Key Git Commands
*Below is a table summarizing key Git commands, syntax, and functionality.**


| Command      | Syntax                          | Functionality                                      |
|-------------|--------------------------------|--------------------------------------------------|
| `git init`  | `git init`                     | Initializes a new Git repository.  |
| `git clone` | `git clone <repo_url>`         | Copies a repository from GitHub.   |
| `git add`   | `git add <file>` or `git add .` | Stages changes for commit.       |
| `git commit`| `git commit -m "message"`      | Saves a snapshot of the project. |
| `git push`  | `git push origin <branch_name>` | Uploads changes to a remote repository.  |
| `git pull`  | `git pull origin <branch_name>` | Fetches and merges updates from remote.  |
| `git branch`| `git branch` or `git branch <branch_name>` | Lists or creates branches. |
| `git merge` | `git merge <branch_name>`      | Combines changes from one branch into another. |







