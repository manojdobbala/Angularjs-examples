Git-Tutorials
==================

This space for practicing various git commands 
git is all about saving snapshots of your project and working with and comparing those snapshots
git init : to make existing files a git repository
git clone: to get a local copy of already existing git repository
git add: to start tracking new files, adding content to staging area
git status and git diff: to see what has been modified and staged 
git status –s:to see short description
git diff: show diff of unstaged changes
git diff --cached: show diff of staged changes
git diff HEAD: show diff of staged or unstaged changes
git diff –stat: show summary of changes instead of full diff
git commit: to record your snapshot in your history
git reset: (most confusing) undo changes and commits
git reset HEAD unstage files from index and reset pointer to HEAD
git reset HEAD –-file :to unstage file
git reset --soft : undo the last commit and put the files back onto the stage
git reset –hard : unstage files and undo any changes made since the last commit
git rm : to remove files from being tracked in git.
git branch: list all branches
git checkout: switch branch
git checkout –b newbranch: creates and swithches to new branch
git branch –d somebranch: delete a branch
git push remote-name: branchname  :delete a remote branch
git merge: merge a branch context into your current one
