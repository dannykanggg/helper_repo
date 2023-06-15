|Command|Description|
|-----------------------------------------------|--------------------|
|`git checkout`                                 | switch between branches
|`git checkout -b <branch_name>`                | create new branch & switch to it
|`git branch`                                   | list of branches
|`git add <file_path>`                          | add <file_path> to staging area
|`git add *`                                    | adds all current tracked changes to the staging area
|`git status`                                   | show list of modified files 
|`git commit -m <commit_message>`               | creates a commit record of all the files in log
|`git log`                                      | shows the list of commits and commit hashes
|`git reset HEAD~1`                             | resets current commit by 1 and keeps changes
|`git reset --soft <commit_id>`                 | resets commit to a commit hash and keeps changes
|`git reset --hard <commit_id>`                 | resets commit to a commit hash and DISCARDS changes 
|`git pull`                                     | pulls the latest from the remote repo from current branch
|`git push`                                     | pushes commits to the remote repo on current branch
|`git push --set-upstream origin <branch_name>` | pushes commits to the remote repo AND creates the branch
|`git merge <branch_name>`                      | merges a local branch to the branch you are currently on
|`git pull origin <branch_name>`                | merges a remote branch to the branch you are currently on
|`git branch --delete <branch_name>`            | delete a local branch




Extra Reference: https://medium.com/edureka/git-commands-with-example-7c5a555d14c
