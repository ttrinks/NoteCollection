Git Cheatsheet
====================

Important Git Commands
-----------

### Create
init - create a repository in the current directory

clone - clone an existing repo

### Browse
status - files changed in working directory

log - history of changes

blame _file_ - who authored each line in _file_

show _id_ - show a commit identified by _id_

diff - changes to tracked files

diff _id1_ _id2_ - changes between _id1_ and _id2_

### Revert
reset --hard - return to the last committed state 

revert HEAD - revert last commit

revert _id_ - revert specific commit

commit -a --amend - fix the last commit

checkout _id_ _file_ - checkout the _id_ version of a file

### Update
pull - pull the latest changes from origin

fetch - fetch latest changes from origin

### Branch
checkout _branchid_ - switch to _branchid_ branch

merge _branch_ - merge _branch_ into another branch

branch _branch_ - create a branch named _branch_

### Publish
commit -a - commit all your local changes

push - push changes to origin

tag - mark a version/milestone


