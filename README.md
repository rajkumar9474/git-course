# Git Tutorial Documentation

This documentation provides a step-by-step guide for basic Git commands and workflows. The tutorial covers initializing a Git repository, adding and committing changes, creating branches, merging branches, and pushing changes to a remote repository on GitHub.

## Initializing Git Repository

```shell
git init
This command initializes an empty Git repository in the current directory.

Adding New Files
 
 
git add git.ipynb
This command stages the specified file for the next commit. Use git add --all or git add -A to add all changes.

Git Staging Environment
After adding files, check the staging environment using:

 
 
git status
This shows the changes staged for commit and untracked files.

Git Commit
 
 
git commit -m "Commit message"
This commits the staged changes with a descriptive message.

Git Commit Log
 
 
git log
View the commit history to see details like commit hash, author, date, and message.

Git Help
 
 
git command --help
git help --all
Use these commands to get help on specific Git commands or see all possible commands.

Git Branch
 
 
git branch main
Create a new branch named 'main'. Use git branch to list branches.

 
 
git checkout branch_name
Switch to the specified branch.

Git Merge
 
 
git checkout master
git merge branch_name
Switch to the main branch and merge changes from another branch.

Git Remote Repository
 
 
git remote add origin repository_url
Connect the local repository to a remote repository on GitHub.

Pushing to Remote Repository
 
 
git push -u origin main
Push changes to the remote repository on the 'main' branch.

Deleting Branch
 
 
git branch -d branch_name
Delete the specified branch after merging changes.

This documentation provides a basic overview of essential Git commands and workflows. Refer to the official Git documentation for more in-depth information.