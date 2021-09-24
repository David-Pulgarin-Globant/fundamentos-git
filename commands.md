git init: to create a git repo
git config --global user.name "%your_github/gitlab/orAliasOfYUourLiking_name%: To set the global author name of commits
git config --global user.email "%your_github/gitlab/orAliasOfYUourLiking_email%: To set the global author email of commits
git config user.name "%your_github/gitlab/orAliasOfYUourLiking_name%: To set the local author name of commits
git config user.email "%your_github/gitlab/orAliasOfYUourLiking_email%: To set the local author email of commits
git status: to check the current status of the working directory, staging and repo
git add %file_route%: to add a single file to staging area
git add .: to add multiple files to staging area
git rm --cached %file_route%: to remove a single file from the staging area
git rm --cached -r .: to remove multiple files from the staging area
git commit -m "%your_message%": This is how you save a change to the repository
git log: Displays history of all the changes that have been committed to the branch
git remote -v: This list the remotes of the repo
git remote add %alias% %remote_repo_uri%: Adds a remote for the repository
git remote remove %alias%: Removes a remote for the repository
git push -u %alias% %branch%: This uploads an untracked branch to the desired remote
git push %alias% %branch%: This updates a tracked branch to the desired remote
git pull %alias% %branch%: This updates a local branch based on what's stored in the remote branch of same name
git branch -v: This list all the existing branches
git branch %branch_name%: This create a new branch (based on the current branch)
git checkout %branch_name%: Allows to switch from one branch to another
git checkout -b %branch_name%: Allows to create a new branch (based on the current branch) and switch to it
git checkout -b %branch_name% %A_COMMIT_HASH%: Allows to create a new branch (based on the branch that contains the hash) and switch to it
git branch -m %branch_name%: Renames an existing branch
git branch -D %branch_name%: Deletes an existing branch
git reset --soft %HEAD/A_COMMIT_HASH%: Deletes a commit from the git history but keeps the changes that were stored with it
git reset --hard %HEAD/A_COMMIT_HASH%: Deletes both, the commit from the git history and the changes that were stored with it
git stash list: Displays a list of stashes
git stash: Generates a new stash entry with a default message
git stash -m "%your_message%": Generates a new stash entry with a custom message
git stash apply: Applies the changes in the stash, but keeps the entry in the stash list
git stash pop: Applies the changes in the stash and deletes the entry from the stash list
git cherry-pick %A_COMMIT_HASH%: Allows to apply a commit from another branch to the current branch
