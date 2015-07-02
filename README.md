HELLO WORLD
===============
1. Steps to create a github repo


DOC
================
1. Sign up on GITHUB
2. Private accounts only on paid version
3. other is BITBUCKET

GIT COMMANDS
=====================
1. Create repo on GITHUB
2. git clone https://github.com/arunpatala/Hello-World.git
3. echo "HELLO World!" > README.md


	a. git add README.md 
	b. git status
	c. git config --global user.email "arunpatala@gmail.com"
	d. git commit -m"adding README; first commit"
	e. git push -u origin master
	f. # give email and password
	g. git status


TODO
===========
1. Passwordless setup
2. branching basics
3. pull requests and merge
4. create WIKI


TUTORIAL
================
https://try.github.io/levels/1/challenges/13
5. command line creation of repo
git remote add origin https://github.com/try-git/try_git.git
6. Remember: The name of our remote is origin and the default local branch name is master. The -u tells Git to remember the parameters, so that next time we can simply run git push and Git will know what to do. Go ahead and push it!
git push -u origin master
7. git pull origin master

DIFF
===============
8. git diff HEAD
9. git diff --staged
10. Remove from staged: git reset octofamily/octodog.txt
11. Revert to last commit :: git checkout -- octocat.txt

creating a branch and working in it
======================================
12. git branch clean_up
13. git checkout clean_up
14. do all changes
15. git checkout master
16. git merge clean_up
17. delete: git branch -d clean_up
18. git push
