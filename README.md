# Getting Started

//TO CONNECT TO THE GITHUB::(only for the first time)

git --version

If it says something like git version 2.x.x, you’re good.

If not, install it:(only work on apple)

xcode-select --install

configuration::

git config --global user.name "Your Name"

git config --global user.email "your@email.com"

on the code editor Terminal::

git init

git add .

git commit -m "initial commit"

git remote add origin https://github.com/omid-tavassoli/TeamProject-KiAgent.git

git branch -M main

git push -u origin main


//TO UPDATE THE CODE ::(after doing the stuff on top only use these)

Git add .

git commit -m "your change"

Git push


//DIAGNOSIS::

git status

git branch -vv

git remote -v

git log --oneline --decorate --graph --all --max-count=15

If status shows uncommitted changes, commit or stash before pulling.

If branch -vv shows your main is behind origin/main, you need to pull.

REMOTE IS AHEAD::

git pull --rebase origin main

git push


//TO UPDATE THE ONLINE SERVER::(only omid do 'thanks')

Npm run build

Npm run deploy