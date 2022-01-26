git init : To initialize the current folder as git repository
git clone <url> :  to bring the git repo from that <url> to the current folder
git add <file> : add the <file> to the staging area.
git commit: opens an editor to add commit message :
git commit -m "message" : helps to provide the comment /message there in 1 line and commits the file.
git log : shows the history of file commits in the git
git log --oneline : shows log/histry in oneine.
git status :shows the status of git operation.
git diff : to find the differences between current uncommited state and the previous git known state.
git diff --staged : compares the file in staging area with the last known state of git.
git diff HEAD~1 : compares the current commit with the 1 previous to it. <relative>
git diff <hash>:compares the current commit with that previous commit <hash> state.
git restore --source <hash> <filename>
git checkout <hash> <filename>
git checkout <hash> : if you forget filename, then will endup in detached head mode.
git switch main / git checkout main : takes us back to previous state.
