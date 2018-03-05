|Command | Effect/Use |
|--------|------------|
|`git stash`| Stashes uncommited changes for later|
|`git stash apply`| Applies previously stashed changes (you can use `git stash list` to list all stashed changes|
|`git cherry-pick <commit hash>`| Pulls in a "cherry picked" commit (specified by hash). The commit can be in any branch or repo.|
|`git rm --cached <file>`| Removes a file from git's tracking index (in case you accidentally git add <file>)|
|`git add -u` | Adds all changes to current commit for files that are already tracked (will not add new files to tracking index)|
