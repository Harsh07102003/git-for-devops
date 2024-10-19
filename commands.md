# Git Commands for DevOps

Configuration
Set global username 
git config --global user.name "<your username>"
Set global email: git config --global user.email "<your email>"

Creating and Navigating Repositories
Create a directory: mkdir git-for-devops
Navigate to directory: cd git-for-devops
Initialize a Git repository: git init

File Management
Create a new file: touch <filename>
Edit a file: vim <filename>
Remove a file: rm <filename>
Create multiple files: touch <filename1> <filename2>
Remove a file: rm <filename>

Git Status and Staging
Check repository status: git status
Add a file to staging: git add <filename>
Add multiple files to staging: git add <filename1> <filename2>
Remove file from staging: git rm --cached <filename>

Committing Changes
Commit staged changes: git commit -m "adding <filename>"
View commit history: git log
View commit history (one line): git log --oneline

Git Branching
Create a new branch: git checkout -b <branch-name>
Switch to an existing branch: git checkout <branch-name>
List branches: git branch

Restoring and Reverting Changes
Restore a file to the last commit: git restore <filename>
Undo changes in a file: git restore <filename>
