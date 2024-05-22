
# Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a repo
 
If we wanted to create a git repo in a new project we create the folder and initialise that repo using git `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md 
open Readme.md
# makes changes to readme.md
git commit -a -m "add read me file"
```

## commmits

## branches

## remotes

## stashing

## merging

## Add

When we want to stage changes that will be included in the commit. We can use the . to add all possible files

```
git add Readme.md 
```

## commits

when we want to commit code we can write git commit which will open up the comit edit message in the editor of choice
```sh
git commit
```
set the gloabl editor
```
git config --logabl core.editor emacs
```

Make a comit and comit message without opening an editor
```sh
git commit -m "add another exclamation"
```

## Gitconfig file
the gitconfig file is what stores your global configurations for git such as email, name and editor and mroe 

```
show the contents of ur .gitconfig file
```
git config-list

When you first install git on a machine you are supposed to set up your name and email

```sh
$git config --global user.name "John Doe"
$git config -- global user.email johndoe@example.com
```

## Status

git status shows you what files will or will not eb comited

## reset 

rest allows you to move staged changes to be unstaged
This is useful when you want to revert all files not to be comitteed


```
get add .
get rest
```
git reset wil revet add all


## push

when we want to push a repo to our remote origin

```
git push
```