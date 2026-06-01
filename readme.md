GIT


Config account:

 git config —global user.name <username>

 git config —global user.email <email>

Refer git configuration:

 git config user.name

git config user.email


Set default branch for repository 

 git config —global init.defaultBranch main

Check git process status:

	git status

Track all command process:
	git log

Add single file into stage:
	git add <file name>

Add all files to stage:
	git add .

Commit the staged files:
	git commit -m “message”

Push the staged files into the remote repository:
	git push origin <BRANCH NAME>

Create new branch:
	git branch <Branch Name>

Switch to new branch:
	git checkout <branchName>

Create and switch branch directly:
	git checkout -b <branch Name>

