Git Course
-----------

`git init `

	to initialize git inside the folder 

`git status`

	checking files status inside repo

`.gitignore `

	is a file that a place to add which file/folder should not be included in repo

`git add .`

	files are went from untracted to added in the staging area

`git add README.md`

	single file added to staging are from untracted

`git reset .`

	files are went back from staging are to untracked

`git commit -m "initial commit"`

	files inside stage area has been commited

`git commit -a -m "add and commit"`

	both add and commit the changes inside the repo

`git log `

	list the information about the last commits have been made

`git remote add origin https://github.com/UPinar/Git_Training.git`

	connects remote repository has been created in Github

`git push origin master -u`

	pushing changes inside remote repo(origin) to the branch(master)
	-u flag is allows git pull command without arguments

`git fetch`

	when changes have been made in webUI, the remote repo will become 1 commit 
 	ahead from local repository. fetch command is getting the last commit from 
  	remote repository

`git merge origin/master`

 	merging the remote repository commit to our local master branch 

	
