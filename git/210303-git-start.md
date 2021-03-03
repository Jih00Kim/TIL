# git start 

## DONE

###shell command 

## GIT INIT

after you create a new repository on github
create a directory with the name of your repository
mkdir repositoryname  ( #it's your working directory)

cd repositorymane
git init  (# so you can create staging area and local repo connected to your working dir)

git remote add origin ___link from github___

git remote 

and if there's any blob( changes or new files) -->  git add (new file name)

git status (chech if the new file is in green color letters)

git commit ( type 'i' to go insert mode and write down info and press esc to get bact to normal mode, then type :wq and enter)

git branch -M main (if your branch is still master)

git push origin main  



## GIT CLONE

after you create a new repository on github ( add a README.md file / License = MIT / gitignore = python)
click code button and copy the clone link of your repository

in the right directory (which is not yet git initialized)
git clone ___  (paste the link you copied from github)
git remote -v  (to check the link already embeded in  origin)

make new directories by mkdir newdirname

only directory with contents( at least a file) will show up when you do git status  
