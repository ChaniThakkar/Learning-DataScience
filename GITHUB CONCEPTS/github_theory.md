##Understand how to use github 


* GIT- Version Control System(VCS)
* GITHUB - Website hosting projects
1. Used for backup
2. provides visual interface
3. other people can access and contribute to it
-------------------------------------------------------------------------
Repository - stores files(have a readme file which gives infor about repo)

Commit - changes done, 1 or more changes done to 1 or more file in the repository

Issues - Bugs

Pull Requests - Contributor change the code & request the owner to pull those changes to the repository

Branches - Master/devel/staging,etc

Forking - Basic github operation
* Go to Repo -> Fork
Forking creates a copy of another repository in your own account
* copy files or if you want to contribute to the repository 

Deleting a forked repository -> Settings -> Delete the repository

CLONE - Copy a repository from the local environment to your desktop
-------------------------------------------------------------------------
* git clone  "link of the repository"
* cd "repository name"
* git remote -v
* git remote add origin
-------------------------------------------------------------------------
Add a new file :
*touch github_theory.md

STAGE THE FILES TO BE COMMITTED
** git status
** git add "file name"  OR  git add .   # add files to be added at once

COMMIT
* git commit -m "Concepts of github"
* git status 

push the changes from local machine to github repo 
Push the master branch to origin remote (github repository) to github

git push origin master - 

Link to refer -  https://www.dataschool.io/git-quick-reference-for-beginners/

-------------------------------------------------------------------------