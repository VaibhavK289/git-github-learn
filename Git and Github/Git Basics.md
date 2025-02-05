
notes reference - https://docs.chaicode.com/terminology/
## Git Basics
### Git Basics 

Git graph is an extension in VSCode that helps in tracking trajectory of git.
Git bash terminal runs almost all commands of linux in windows.

**Git** - it is a software.
**Github** - it is a git hosting online service.
**Version Control System** - it is used to maintain the history of code.

#### Other version control software 
SCCS - Source Code Control System, Subversion, CVS, Perforce, mercury.

## Git Terminologies

1. **Repository** - a container that stores all the files and directories (code).
2. **commit** - way to save change and make them permanent in the repository.

## Git Commands 

3. **Git --version** - check the version of git software.
4. **git status** - check current state of repository.
5. **git config --global user.email "useremail@id.com"** - use to change global user emailId.
6. **git confid --global user.name "username"** - use to change the global username.
7. **git config --list** - use to list all the configuration settings.
8. **git init** - create a new folder and initialize as a git repository.
9. **git config --global init.defaultBranch  name** - change name of the default branch.
10. **git branch branchname** - create a new branch.
11. **git branch -m name** - changes name of the current branch to specified name.

![[Git Status image.png]]
 
Note 
12. .git is a hidden folder and inside that data is stored as a database.
13. before creating a repository check the git status to avoid any overwriting of the data.


## Complete git work flow


		write ---> add ---> commit 

				git init
					|
					|
		<----- working directory
		|
		|
		git add
		|
		|
		  ----- staging area ------>
								|
								|
							git commit 
								|
								|
	      <--------- Repo ----------
	    |
		|
	git push
		|
		|
		 ----------> Github
