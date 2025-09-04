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

git create --all --message "tests git rm,mv and gt crereate --all"
//this single command stages all files, creates a commit, and pushes a branch:


