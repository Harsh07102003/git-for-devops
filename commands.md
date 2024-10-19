# Git Commands for DevOps

1. Creating and Navigating Repositories
Create a directory: mkdir git-for-devops
Navigate to directory: cd git-for-devops
Initialize a Git repository: git init

2. File Management
Create a new file: touch hello.txt
Edit a file: vim hello.txt
Remove a file: rm hello.txt
Create multiple files: touch nibba.txt nibbi.txt
Remove a file: rm nibbi.txt

4. Git Status and Staging
Check repository status: git status
Add a file to staging: git add nibbi.txt
Add multiple files to staging: git add nibba.txt
Remove file from staging: git rm --cached nibba.txt

5. Committing Changes
Commit staged changes: git commit -m "adding nibba nibbi"
View commit history: git log
View commit history (oneline): git log --oneline

6. Git Branching
Create a new branch: git checkout -b dev
Switch to an existing branch: git checkout master
List branches: git branch

8. Restoring and Reverting Changes
Restore a file to the last commit: git restore nibbi.txt
Undo changes in a file: git restore file1.txt
