
// To create a git project
git init

// To check on which branch we are and to check updated file list
git status

// Add files to staging
git add, git add .

// To commit our changes
git commit -m 'comment u wished'

// To check commit log
git log

// to create a new file and add to ignore some file types. 
touch .gitignore

// create a new branch 
git branch cssBranch

// switch to new branch
git checkout cssBranch
    -- changes in branch
    touch test.css
    git add .
    git commit -m 'initial branch commit'

// mege master and cssBranch(make sure on target branch)
git checkout master
git merge cssBranch

// Checking for conflicts, so adding on master.
// These lines are under conflict, lets try  for merge.


// ************** git mertool like tortoise can be used for resolving merge conflick ***************** ////////

// If you create a new and do not commit it, it will be available for different branches.

// You can save the state of your branch for stashed file using git stash command and switch between branches.
git stash // it will save this file for that particular branch
git stash apply // once you are back this command will give you the file back. and you can apply it to diff branch

