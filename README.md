# gitSprint

1. Set up your repository locally 
  mkdir _folderName_
  cd _folderName_
  git clone https://github.com/sat-wik/gitSprint.git
  cd gitSprint
  git pull (should be up to date) 

2. Create a branch and your local commit 
  git checkout -b _branchName_
  Create a file called assignment.txt 
  Populate the file with the names of you
  Create a commit 

3. Rebase with main and resolve merge conflicts 
  git checkout main  
  git pull origin main 
  git checkout _branchName_
  git merge main 
  resolve merge conflicts in text editor 
  add, commit, and push your changes 

4. Create a pull request for your branch 
