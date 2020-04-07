# Github
My Github Learnings
[[Visual Notes]](https://www.draw.io)
[[1]](https://www.youtube.com/watch?v=3a2x1iJFJWc)|[[2]](https://guide.freecodecamp.org/git/git-pull/)|[[3]](https://help.github.com/en/github/using-git/about-remote-repositories)

![](https://i.ibb.co/0X29fQ2/Git-Work-Flow.png)

## Create New Branch
* Creating a new branch from an existing branch and checkout the newly created branch: git checkout -b <branch-Name>
  
## Pull
git pull is a combination command, equal to git fetch + git merge.
* git pull
* git pull 

## Merge Branch
* Merge current branch to change of any other branch 
* git merge <branch-Name> 

## Stash [[1]](https://www.atlassian.com/git/tutorials/saving-changes/git-stash#re-applying-your-stashed-changes)
* It is the process of keeping the current changes and pulling the lattest from remote.
* It is also useful while switching from one branch to another branch without loosing the current change
* They are stored in the stack format
* git stash
* git stash save "add style to our site"
* git stash apply
* git satash pop
* git stash list
* git stash clear

## Git Commands
* git config user.name "name"
* git config user.email "email"
* git init (Atleast one commit to see master branch listed by the git branch command)
* git remote
* git remote -v
* git remote add <name> <url>
* git add README.md
* git commit -m "first commit"
* git remote add origin git@github.com:codewithbraja/CustomComponents001.git
* git push -u origin master
* git fetch --dry-run
* git log --oneline --graph

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

## Remote branch delete
1. git branch -d branch_name
2. git push <remote_name> --delete <branch_name> (options can also be used if you want to delete a “tag")
3. git push -d (push your local branch to remote and delete your local)
