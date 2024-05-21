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

`git pull`

 	This command is actually does git fetch + git merge commands combined job
  	when -u flag has been used in push command we don't need to specify 
   	remote branch name in git pull command

`git pull origin/master`

 	when -u flag has not been used we will specify remote branch name.
	
`git clone https://github.com/UPinar/CppLessons.git`

	cloning repository from github to the folder that we are in.

`git clone https://github.com/UPinar/CppLessons.git Cpp_Lessons_Folder`

	cloning repository from github to a folder called Cpp_Lessons_Folder

`git branch`

	this command will list all branches 

`git branch -M main`

	this command will change master branch name to main

`git branch my_new_brach`

	this command will create a seperate branch from the main(master) branch 

`git branch -d my_new_branch`

	this command will delete the branch called my_new_branch

`git push -u origin main`

	this command will create new brach in the remote repository 
	think about you created main branch in local repo and you want to create 
	that branch also in remote repository

`git push origin --delete branch_name(master)`

	if you have 2 branch in github account main and master
	and you want to delete master branch only want to have main
	this command is pushing origin(local repo) and deleting remote repo

`git checkout test_branch`

	this command will checkout to test_branch from master or main branch 

`git checkout -b test2_branch`

	this command will create a branch called test2_branch in local repo
	and checkout to test2_branch from master or main branch 

`git merge test_branch`
`git merge --abort`
`git commit -am "merge commit"`

	think about X branch has some changes in file A and Y branch also 
	have some changes in the same file same lines. Both changes 
	have been commited in their branches. 
	Now X branch wants the changes happened in Y branch so it runs
	-git merge Y- command but merge confict happened.
	We can abort the conflict by using -git merge --abort-
	Accept X or Y branch changes or both. 
	At last we need to have a merge commit.

