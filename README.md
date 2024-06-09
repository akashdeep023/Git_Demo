# Git & Github Command 

## Global To Local 
    git clone (repo https link) -> add repository (paste link click mouse right)
    check list              -> ls 
    open repo               -> cd (file name)
    create file             -> touch (file name)
    check file status       -> git status
    untracked files | modified file etc
    add file                -> git add (file name) || add all file -> git add . 
    check file status       -> git status
    commit file             -> git commit -m "(add massage)"
    check file states       -> git status
    push to local to global -> git push origin main
    check file states       -> git status

## Local To Global
    Create folder and push repo
    cd (folder name)
    git push origin main
    git init                -> used to create a new git repo
    git remote add origin (repo link)
    git remote -v           -> check remote
    git branch              -> check branch
    git branch -M           -> rename branch
    git push origin main    -> push local to global
    git commit -am "msg"    -> add & commit (modified)
    git push -u origin main -> set branch - main , again push enter command -> git push
    
## Git Branches
    git branch                          -> check branch
    git branch -M                       -> rename branch
    git checkout (branch name)          -> to navigate (change branch)
    git checkout -b (new branch name)   -> create new branch
    git branch -d (branch name)         -> delete branch

## Git Merging code
    git diff (branch name)      -> to compare commits,branches,files & more
    git merge (branch name)     -> to merge 2 branches

## Pull Request
    git pull origin main -> pull global to local

## Fixing Mistakes
    git reset (file name) ya git reset  -> staged changes ( back one stage 'git add' ka)
    git reset HEAD~1                    -> commited changes (back one commite 'git commit' ka)
    git reset (commit hash)             -> commited changes (for many commits )
    git reset --hard (commit hash)      -> commited changes (for many commits remove code )

## How to create a pull request in other github account.
    github---------------
    click fork                    -> fork repository
    copy link                     -> copy fork repo link 
    terminal-------------
    mkdir folder_name             -> create folder
      cd folder_name              -> open folder
    git clone <repo-link>         -> clone repository 
    cd repo                       -> open repository
    file exploral -------
    copy folder                   -> copy project folder 
    paste repo folder             -> paste project in repository
    terminal-------------
    git status                    -> check status	(show untracked)
    git add .                     -> add file or folder
    git commit -m "add file"      -> commit file or folder
    git push origin branch_name   -> push local to global
    github---------------
    refresh github account 		
    open repo
    click Pull requests
    click New pull request
    select branch_name 
    click Create pull request
    type Some message
    click Create pull request

# Git_Demo
This is my first repository..
# Coder
Akash Deep 
# Teacher
Sharadha khapara

## Thanks for visit..

