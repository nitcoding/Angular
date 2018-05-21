# Angular
AngularJS

Created an application in local folder & ran following commands in that folder:
git init
 git status
git add [filename1 filename2]
git commit -u "CommitComment"
 git log

Created a repo via github & ran foll commands:
git remote add origin https://github.com/nitcoding/Angular.git (to make the connection b/n local repo & hub repo)
 git remote -v
git push -u origin master

git fetch origin master
git merge origin/master (When u want to resolve conflicts & merge)

git pull origin master (When u want take latest and avoid all conflict)

git remote remove origin (to remove the connection b/n local repo & hub repo)

[
When a hub & local are outta sync and u wish to push local to hub then u first have to pull. But u cant just pull if they r not in sync, it'll give error. U have to do following:
git pull origin master --allow-unrelated-histories
]

git clone https://github.com/nitcoding/Angular.git
[then u'll do some changes & 'add commit push' move them up in hub]
