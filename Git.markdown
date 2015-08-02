# Git
tags: git
___
[TOC]

## Get git and set it up

- [git Windows version download](http://msysgit.github.io/)
run the following command after install the git
> `$ git config --global user.name "Your Name`
> `$ git config --global user.email "email@example.com"`

 then the config will store in the `.gitconfig` file in the root directory of your git installation

- create the local repository
 ```
$ mkdir learngit
$ cd learngit
$ git init
```
then there is a folder named `.git` in learngit, it is store the file which will be used by git . then this directory will be managed by git

## Command 
> 
1. `git help <command>`
2. `git add`
3. `git commit -m "comment"`
4. `git status`
5. `git log`
6. `git checkout -- file`
7. `git checkout HEAD <file>`
8. `git reset --hard HEARD^`
9. `git rm`

## Remote repository
1. Run the following command to create SSH key which used to transfer file between local to GitHub
> `$ ssh-keygen -t rsa -C "youremail@example.com"`

 then you will find a folder named `.ssh` in your git root folder. and your can add the correspoding public key to GitHub
 
2. git branch
 查看分支：`git branch`

 创建分支：`git branch <name>`

 切换分支：`git checkout <name>`

 创建+切换分支：`git checkout -b <name>`

 合并某分支到当前分支：`git merge <name>`

 删除分支：`git branch -d <name>`
