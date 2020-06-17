# Git-basics
We did an exercise on editing a repository offline using **terminal commands**. These are the **commands** you need, in bold.
This assumes you have git, github, and a repository (or repo) which you can access in github.

## 1. moving to the right folder

a) Use dir or pwd to see where you are.

b) **ls** to show the folders in the current directory

**ls -a** to show more information on the files in the folder

c) Use **cd** to change directory.

**cd** to go to the home directory

**cd docs** to go to  a specific folder named docs

(repeat until you are in the folder you need to be)

you can also use **cd ..** to move one directory up and **cd /..** to move to the home directory

## 2. cloning a repository (download it to your current directory to work in it)

a) go to the github page for the repository

b) click the green button to copy the LINK (it ends with .git)

c) We now start work in git. All git commands start with **git**.

Use **git clone LINK** to start working in the repository

d) you are now not working in the repository yet. You still need to go there using **cd NAME** where NAME is the name of the repository

e) you are in the repo now!

## 3. opening a branch and editing it

 a) use **git branch -a** or **git branch -av** to show all branches. The branch you are now in will be green or white.
 
 b) **git checkout BRANCH** to start working in the branch named BRANCH (**git checkout development** in our exercise)
 
 c) **ls** to show the files in the repo to know which files you can open
 
 d) **open FILENAME** to open the file named **FILENAME**. If **open** doesn't work you can also open it manually by going to the folder in your file browser
 
you are now editing a file!

## 4. push your changes to the repo

a) once you are done improving the file, save it.

b) then do **git add** to move your file to your staging area

c) then do **git commit** to commit the file to your local repository

you can also do step b and c at the same time by doing **git commit -a**

d) then do **git push origin**

(origin is the online repo)

## 5. merging changes from branch A to branch B

a) go to branch B (use **checkout B**)

b) do **git merge A**
