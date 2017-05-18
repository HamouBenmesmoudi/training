my login app
this is my app.

git branch otherRepo // create a branch otherRepo
git checkout otherRepo // switch to otherRepo




// create local repo.
git init

//link local repository to remote repository
git remote add origin "https://github.com/HamouBenmesmoudi/training.git" 

// populate local repo.
git pull origin master

git status

// add all changes.
git add . (or -A au lieu du point)

// commit to the index.
git commit -m "new commit: add file and modify file"

git log

// create a branch.
git branch firstbranch

// switch to the new branch
git checkout firstbranch

// create a new file.
git add .
git commit -m "making change in firstbranch"


