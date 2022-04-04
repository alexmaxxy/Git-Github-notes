# Git-Github-notes

# Basic's of git.

->git clone ____ // get my own copy of a repository

->git add --all // after adding or changing any files in my repository

->git commit -m "I made some changes, why?"

->git push // to send my local code to the central repository

->git pull // pull code to local system from central repository

# STEPS to Clone a repository :-

*Go to command terminal
*cd path where you want that file
*Open Github's repository which you want to clone .
*Click on Clone button
*Link will get displayed , click on copy button
*Come back to command line
*git clone link(copy) (without .git) 8.Enter

->If you want to clone a single repository use - git clone --single-branch --branch branchname repo-to-be-cloned

# Steps to push a file in a existing repository:-

*On your computer, move the file you'd like to upload to GitHub into the local directory that was created when you cloned the repository. 2.Open Terminal. 3.Change the current working directory to your local repository.
->git add --all

->git commit -m "Add existing file" 6.git push

# STEPS TO KEEP A FORKED REPOSITORY UPDATED : -

*Go to terminal
*cd path to the local directory path
*git remote add upstream url ( of the repository from where you forked ) - this is needed for the first time only .
*git pull upstream main(or master) -- this need to be done everytime you want the updated project .
*Steps to push a file into a new repository :-

*go to terminal and change directory to the path of the project/folder

->type git init - this is to make a local repository
->type git add . - to add all files
->optional - type git status to check the file to be commited
->type git commit -m "first commit" -- the message can be anything
->copy the repository url from github
->type git remote add origin url
->type git push -u origin master(or main)
Done.
