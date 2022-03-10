# GitEssentials
This is a guide with on git commands 

## Requirements
1. Create github account
2. Create a repository (a storage unit for your code)
3. Install git bash

## Git clone 
cloning is copying from github to your local machine
1. open cmd 
2. mkdir GitEssntials
3. cd GitEssntials
4. git clone https://github.com/victoriawasonga/GitEssentials.git git_essentails (takes in an optional argument of folder name in this case git_essentials 
5. If you want to clone a particular branch of this repository, you’d want to do something like this
    git clone https://github.com/JamesOkunlade/old-apple.git -b branch-name
    
## Git checkout
It’s a best practice to create different branches for different features instead of working on the master branch directly. When all features have been deemed 
to pass certain tests and requirements, then you can merge them into the master branch. At different times, you will have to checkout to the particular repository 
branch you want to work on, and you can do this with the following command.

If the branch had already been created:
1. git checkout branch-name

And if you’re just creating the new feature branch
2. git checkout -b branch-name

## Git pull
Your team or pair programming buddy will change different branches of a repository, and you should always pull these new changes before you start writing code.
On your terminal, checkout to the branch you’ll be working on, and run the git pull command. The recent changes will be pulled to your local repository.

## Git Add 
The add and commit Git commands are almost always used together. Think of them as capture and save. You can’t save a thing if you don’t capture it first. Hence, the add command should always precede the commit command. While you use the add command to point at the particular file you want to capture in its current state, you use the commit to save a copy of what you captured.To capture all the files (except those excluded by Git ignore), you will use After taking the snapshots, you will then have to commit and save your snapshots to your local repository using the code bwlow The commit message should explain the peculiarity of the snapshot you’re saving

1.  git add . (all)
2.  git add index.html
3. git commit -m ‘commit message’
4. git add index.html && git commit -m ‘footer html structure created( You can do the two together with the && operator as shown below)

## Git push
Just like saving your snapshots to a Google Photos album for whomever you share the album with, think of git push as sending your local repository to the remote repository for others to access.

1. git push -u origin branch-name


## git status 
## git merge
## git init
## rollback 

## ssh


