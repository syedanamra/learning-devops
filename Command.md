# Git Commands 

## 1. Create Project Directory
Create a new folder for the Git project.

```bash
mkdir git-for-devops
cd git-for-devops
pwd
2. Initialize Git Repository

Initialize Git inside the project directory.

git init
ls -a
git status
3. Create Files

Create files inside the repository.

touch Nibba.txt Nibbi.txt
ls

Create and edit a file using Vim.

vim hello_doston.txt
cat hello_doston.txt
4. Check Repository Status

Check the current state of the repository.

git status
5. Add Files to Staging Area

Add files to the staging area before committing.

git add Nibba.txt
git add Nibbi.txt

Add all files at once.

git add .
6. Remove File from Staging Area

Remove a file from the staging area.

git rm --cached Nibba.txt
7. Commit Changes

Save the changes permanently in Git.

git commit -m "Nibba Nibbi"
8. Remove Files from Repository

Delete files from the repository.

git rm Nibba.txt
9. Restore Files

Restore deleted or modified files.

git restore Nibba.txt
git restore --staged Nibba.txt
10. View Commit History

Check the commit history.

git log

Exit from log view.

q
11. Create a New Branch

Create and switch to a new branch.

git checkout -b dev
12. Switch Branch

Move between branches.

git checkout master
git checkout dev
13. Add and Commit Changes in Branch
touch nibbu.txt
git add nibbu.txt
git commit -m "adding nibbu"
14. Check Command History
history
Basic Linux Commands Used
pwd
ls
ls -l
ls -a
clear
