# BELAJAR DASAR GIT

* Command Dasar GIT
 > Configuration
 	- git config --global user.name "Sample Username"
 	- git config --global user.email "sample.email@gmail.com"

 > Start Repository
	- git init
	- git status

 > Stagging file
	- git add <file-name>
	- git add <file-name> <second-name>
	- git add .
	- git add --all
	- git add -A
	- git rm --cached <file-name>
	- git reset <file-name>

 > Committing to Repository
	- git commit -m "Message commit"
	- git reset --soft HEAD^
	- git commit --amend -m <enter message>

 > Pulling and Pushing to Repository
	- git remote add origin <link>
	- git push -u origin master
	- git clone <link>
	- git pull

 > Branching Repository
	- git branch
	- git branch <branch-name>
	- git checkout <branch-name>
	- git merge <brach-name>
	- git checkout -b <branch-name>
