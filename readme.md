# Git and GitHub

Git download and install from Internet.

Open Git Bash(or command line)


`$ git --version`			//in the project folder

`$ git init`   			// first command - initialization

`$ git status` 			// cutent status

`$ git add index.html` 		//add file to repository

`$ git rm --cached index.html` 	// stop tracking 

`$ cls` 				//clear

`$ git add .`			// add all files after changing

`$ git commit -m "first commit"`	//saving changes in the local repository

**.gitignore**			// untracked file list and

`$ git add .`


`$ git branch`			// review branch list

`$ git branch test`		// create new branch "test"

`$ git branch -D test`		// delete branch "test"


`$ git branch readme`		// create new branch "readme"

`$ git checkout readme`		// swith to "readme" branch

`$ git checkout -b new`		// create "new" and swith to "new"

`$ git checkout master`		// switch to master

`$ git merge readme`		// insert readme to master

`$ git branch -D readme`		// delete "readme" branch


_**github.com**_   new repository		// create new repository

local credentials

`$ git config --global user.name`			// review local user

`$ git config --global user.name "Illya"`		// create local user

`$ git config --global user.email`		// review local email

`$ git config --global user.email "il@mail.com"`	// create local email



`$ git remote add origin https://github.com/ILLYAKO/git-course.git` // conection local repository to remote

`$ git push -u origin master`		// push local changes to online repository.


`$ git add .`				// after the changes

`$ git commit -m "added console"`

`$ git push`


`$ git pull`		// Start work with to pull changes to local

`$ git clone`		// Clone project from online repository.







