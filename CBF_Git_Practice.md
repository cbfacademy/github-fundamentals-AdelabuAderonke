#NOTES ON WHAT I LEARNT ON GIT
Git is a version control system. It is used mainly for collaboration and keeping track of code changes.
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere
Repository: a place where we store our files. 
Remote:It can be a folder on cloud or on some websites like GitHub, GitLab or Bitbucket or anywhere. It serve as a backup if your machine was crashed by power fluctuations or any other problems. 

###Commands in git
- Git –version: This is used to check the version of git
	$ git –version
- Git clone: It is used to make a copy of  that repo in a new directory. 
$ git clone repo url
- Git add:Moves changes from the working directory to the staging area 
- Git status: It displays information about a current repository that is the state of the repository by listing out all the files in the repository
	$ git status
- Git pull: It is used to fetch and update content on the local repository from the remote repository 
	$ git pull
- Git init:Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.
          $  git init
- Git push: A simple way of sending update to the origin. Latest update made on the Local repository is made available on the remote repository,
- Git commit : The commit command is used to save your changes to the local repository.  
 	$ git commit -m “ your commit message”
- Git merge:A way to integrate changes from different branches. After forking the project history with git branch, git merge lets you put it back together again.
	$ git merge
- Git branch:List all of the branches in your repository. 
	$ git branch 
- Git checkout: Allow you to change from one branch to another.
	$ git checkout <branchname>
	- $ git checkout -b <branchname>  - This create a new branch and checkout to that branch
- Mkdir : This is used to create a new folder  or root directory
$ mkdir directory_name
  
  
  ###Confused? 😕
  Yes, I am still confused if I can create  a repository locally without having to create a repository on Github. Once I push from the terminal it will appear automatically.
  I have always dreaded Git, CBF is making it interesting 😎




