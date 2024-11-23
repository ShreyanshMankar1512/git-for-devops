# Git Commands Cheat Sheet

## 1. **Basic Setup**
These commands are used to configure your Git environment.

### Set Username and Email
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
2. Repository Initialization
Commands to create and initialize a new repository.

Initialize a New Git Repository
bash
Copy code
git init
Check Repository Status
bash
Copy code
git status
3. Working with Files
Commands related to adding, removing, and viewing file statuses in Git.

Add Files to Staging Area
bash
Copy code
git add <file-name>   # Adds specific file
git add .             # Adds all changes
Remove a File from Staging Area
bash
Copy code
git rm <file-name>
View the Status of Files
bash
Copy code
git status
Restore Changes to a File
bash
Copy code
git restore <file-name>
4. Committing Changes
Commands to commit changes to your local repository.

Commit Changes
bash
Copy code
git commit -m "Your commit message"
View Commit History
bash
Copy code
git log
git log --oneline   # Shortened commit history
5. Branching
Commands for managing branches in a Git repository.

Create a New Branch
bash
Copy code
git branch <branch-name>
Switch to Another Branch
bash
Copy code
git checkout <branch-name>
Create and Switch to a New Branch
bash
Copy code
git checkout -b <branch-name>
List All Branches
bash
Copy code
git branch
6. Merging
Commands related to merging changes from one branch to another.

Merge a Branch into the Current Branch
bash
Copy code
git merge <branch-name>
7. Viewing Changes
Commands to review the changes in your working directory and repository.

View Changes Made to Files
bash
Copy code
git diff
8. Remote Repositories
Commands to work with remote repositories.

Add a Remote Repository
bash
Copy code
git remote add origin <repository-url>
Push Changes to a Remote Repository
bash
Copy code
git push origin <branch-name>
Pull Changes from a Remote Repository
bash
Copy code
git pull origin <branch-name>
Clone a Remote Repository
bash
Copy code
git clone <repository-url>
9. Undoing Changes
Commands to revert or undo changes in the repository.

Discard Changes in a File
bash
Copy code
git checkout -- <file-name>
Undo a Commit (Before Pushing)
bash
Copy code
git reset --soft HEAD^1  # Undo the last commit but keep changes staged
git reset --hard HEAD^1  # Undo the last commit and discard changes
10. Stashing Changes
Commands to temporarily store changes you don’t want to commit yet.

Stash Your Changes
bash
Copy code
git stash
Apply Stashed Changes
bash
Copy code
git stash apply
List Stashed Changes
bash
Copy code
git stash list
Drop a Stash
bash
Copy code
git stash drop
11. Working with Tags
Commands to work with tags in Git.

Create a Tag
bash
Copy code
git tag <tag-name>
List All Tags
bash
Copy code
git tag
Push Tags to Remote
bash
Copy code
git push origin <tag-name>
12. Collaborating with Others
Commands for working with teams and contributing to a project.

Clone a Repository
bash
Copy code
git clone <repository-url>
Fetch Latest Changes from Remote
bash
Copy code
git fetch
Pull Changes from Remote Repository
bash
Copy code
git pull origin <branch-name>
Push Changes to Remote Repository
bash
Copy code
git push origin <branch-name>
View Remote Information
bash
Copy code
git remote -v
Remove a Remote
bash
Copy code
git remote remove <remote-name>
Note: Replace <file-name>, <branch-name>, and <repository-url> with the appropriate file names, branch names, and repository URLs.

css
Copy code

This version doesn't have the "copy code" labels, keeping it in a cleaner markdown format.
