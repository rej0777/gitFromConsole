# gitFromConsole
tests of commands git from console

git clone https://github.com/rej0777/gitFromConsole.git
//or
git init
Initialized empty Git repository in D:/GitRepoTest/test1/.git/

//if needed
  git config --global user.email "rayearth777@wp.pl"
  git config --global user.name "rej777"
  
git status
git add.
git commit -m "project start"

//we are making changes to the files, new code
git status
git commit -a "program code change1"
git push origin main

//
git pull

//
git branch -c sprint1
$ git branch -a
* main
  sprint1
  
git rm saturn5.py //deleting git file
git mv saturn5.py saturn55.py //rename file

git add .
git commit -a -m "tests rm and mv commands"
git push

git commit -a -m "nesesery comit before checkout"
git checkout sprint1
git merge main // pull all changes from main to sprint1

git rm saturn9.py
git add .
git commit -a -m "commit in sprint1 "
git push origin HEAD:sprint1
