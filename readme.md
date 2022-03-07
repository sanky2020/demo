# Demo folder for demonstrating Git Commands;

### 1) git config --list 
* To see the configuration list
### 2) git clone "clone-url" 
* makes a copy of remote repo into local system within specified folder.
### 3) git branch 
* Lists all the available branch alongwith the current working branch.
### 4) git checkout -b "branch-name"  
* "b" flag creates a new branch with the "branch-name", checkout switches to this newly created branch 
### 5) git status
* gives the status of the newly-created-files/modified indicating in red color
* Green color indicates that the files are added to staging area.
### 6) git add .
* Adds all the newly-created/updated files to the staging area.
### 7) git commit -m "message"
* "m" flag is used for adding any "message" while doing commit
### 8) git pull origin main
* Pulls all the latest files from remote repo into present working directory
#### If there is any conflicts repeat steps 5,6,7,8,9; else
### 9) git push origin "branch-name"
* pushes the code to remote repo to the specified branch.
