# Git instructions

## Tutorial

1. `git init`  
**to start git in a directory**
1. `git status`  
**to see the status on the directory**
1. `git checkout -b main`  
**to create a new branch**
1. `git branch`  
**to see the list of available branches**
1. `git checkout <branch-name>`  
**to change branches**
1. `git add .`  
**to add all changes made**
1. `git add index.ts`  
**to add a single change**
1. `git commit -m '<describe-your-commit>'`  
**tips: <feat/add/bug/debug/fix | message>**
1. `git push -u origin <branch-name>`  
**to push the changes to github**
1. `git remote add origin <repository-url>`  
**to set the repository**
1. `git pull origin <branch-name>`  
**to pull all changes from github to your local machine**
1. `git pull origin <branch-name> --allow-unrelated-histories`  
**to pull all changes from github, but ignoring unrelated histories**
1. `:wq #<to exit vim>#`  
**to exit vim**

To see the status

- src
  - app
    - index.ts
  - interfaces
    - index.d.ts

    git add .
    git add index.ts

* To see the changes
`git status`