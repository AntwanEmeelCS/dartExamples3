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
git checkout [BranchName]
git checkout branch1
~~~~

3. Update Branch with same method

~~~~
git status
git add .
git commit -m "Branch Commit Message"

git push -u origin [BranchName]
git push -u origin branch1
~~~~