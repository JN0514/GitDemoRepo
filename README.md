# GitDemoRepo

Repository contains the git commands and its explanation.

Basic Commands:
git clone
git init
git status
git add
git commit
git commit -am 'commit message' -  this '-am' tag, adds changes to Stages and commit changes with the message. this works only for modified file. 

git push --set-upstream origin "localBranchName"
git push origin branchname
git push
git checkout 'branchName'
git checkout -b 'branchName'
“git diff ‘branch name’” - shows difference of the branch from the current branch.
git branch - to display branch names that is checkout locally.
git branch -d 'branch name' - to delete branches
git merge 'branchName' - Before this command, be in the branch from which the incoming branch to be merged. Replace branchname with the name which you want to merge into this current branch.
git merge --abort


git reset "filename" - to unstage a staged file
git reset HEAD~1  - To undo previous commit, and move the last commited files to unstaged changes.
git reset 'commit hash' -  Visit to the particular commit and removes other commits after this commit hash, and moved all the commited files after this commit hash to staged.
git reset --hard 'commit hash' - Visit to the particular commit and removes every file and commits after this commit hash.

git reset —hard - resets any changes in the tracking file  and pointing to the 



fork
pull request
