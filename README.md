# Github
My Github Learnings
[[Visual Notes]](https://www.draw.io)
[[1]](https://www.youtube.com/watch?v=3a2x1iJFJWc)|[[2]](https://guide.freecodecamp.org/git/git-pull/)

![](https://i.ibb.co/0X29fQ2/Git-Work-Flow.png)

## Create New Branch
* Creating a new branch from an existing branch and checkout the newly created branch: git checkout -b <branch-Name>
  
## Pull
git pull is a combination command, equal to git fetch + git merge.
* git pull
* git pull 

## Merge Branch

## Git Commands
* git config user.name "name"
* git config user.email "email"
* git init
* git remote
* git remote -v
* git remote add <name> <url>
* git add README.md
* git commit -m "first commit"
* git remote add origin git@github.com:codewithbraja/CustomComponents001.git
* git push -u origin master
* git fetch --dry-run

## Git Errors & fix
1. remote: HTTP Basic: Access denied : Change password in Credential Manager

## Upstream & Downstream
When talking about a branch or a fork, the primary branch on the original repository is often referred to as the "upstream", since that is the main place that other changes will come in from. The branch/fork you are working on is then called the "downstream".

## Local repository in github
1. Create a remote repository in github
2. Delete all the git files in local project folder:rd .git/S/Q
3. git init
4. git add .
5. git commit -m "ur message"
6. git remote add origin **link**
7. git push -u orgin master

