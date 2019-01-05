
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


