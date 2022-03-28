# ```git``` Cheatsheet

## Working with local repository ##

- In order to create a new repo use ```git init```
- Checking the current status of the repo (see what changed and what doesnt) ```git status```
- Add files to the staging area ```git add <list of files>```
- You can quickly add all files to the staging area by using ```git add .```
- You can create a commit by using ```git commit -m <message>```

## Working with remote repository ##

- In order to pull the remote commits from the origin you use ```git pull```
- In order to push the local commits to the origin you use ```git push```
- If you have checked out a branch for the first time, when you push it, you might have to specify how it maps onto a branch on the remote. Thus you use ```--set-upstream (or -u)``` on push. Like this: ```git push -u origin <branch-name>```. You only have to do it upon the first push.
