# My New Repo

## Connect to a repo with VS Code

This repo is created with the help of ChatGPT

1. First Create and Open Your new project folder

~~~~ 
mkdir [destination folder]
mkdir H:\AntwanEmeel\myDescendants\dartExamples3 
~~~~

2. Create a new readme markdown file

~~~~ 
code [new file name]
code readme.md 
~~~~

3. Write some markdowns like this!

4. Initialize git

~~~~ 
git int 
~~~~

5. (Optional) get branch status (after saving all files)

~~~~ 
git status 
~~~~

6. Add files to the next commit

~~~~ 
git add [filename1] [filename2] ....etc 
~~~~

OR add ALL files

~~~~ 
git add . 
~~~~

7. Commit changes to current branch (currently master)

~~~~ 
git commit -m "Your message should imply your changes done" 
~~~~

8. Create a repo online on your github Account, copy its https link and use the following command to add a remote destination, this is needed once.

~~~~ 
git remote add origin [Repo HTTPS Link]
git remote add origin https://github.com/AntwanEmeelCS/dartExamples3.git
~~~~

9. Push your changes to your master branch

~~~~ 
git push -u origin master 
~~~~

----------------------------------------------------------------------------
## Branching Work

1. Create a branch

~~~~
git branch [BranchName]
~~~~

2. Move from current branch to another (note branch name change on your status bar after using ths command)

~~~~
git checkout [branchName]
~~~~

3. commit changes to branch as following
~~~~
git status
git add .
git commit -m "Branch Commit Message"

git push -u origin [BranchName]
git push -u origin branch1
~~~~

4. merging changes (move to destination branch first)

~~~~
git checkout master
git merge branch1
~~~~

5. If conflicts happen, resolve them with VS Code.

6. Delete old branch if it's no longer needed (local work)

~~~~
git branch -d [branchName]
git branch -d branch1
~~~~

7. Delete old branch (online repo)

~~~~
git push origin --delete [branchName]
git push origin --delete Branch1
~~~~
----------------------------------------------------------------------------------
## Pulling Changes From Remote To Your Local Repo

### Always refresh your local as your partners may update the repo

~~~~
git pull origin master
~~~~
