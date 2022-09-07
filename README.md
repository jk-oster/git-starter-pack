# git-starter-pack

### Git Setup and initialize
- initialize an existing directory as a Git repository `git init`
- retrieve an entire repository from a hosted location via URL `git clone [url]`

### Git Stage / Git Add
- show modified files in working directory, staged for your next commit `git status`
- add / stage a file as it looks now to your next commit `git add [file]` / `git add .` to add all files form current directory
- commit your staged content as a new commit snapshot `git commit -m '[Commit message]'`

### Git Branches & Git Merge
- list your branches. a * will appear next to the currently active branch `git branch`
- switch to another branch `git checkout [branch name]`
- create new branch `git branch [branch name]`
- merge specified branch into currently active branch `git merge [branch name]`

### Git Sharing & Updating
- upload current branch commits to the remote repository `git push`
- download, fetch and merge any commits from the remote branch `git pull`

### Git Work in progress & Temporary Commits
- temporarily save changes without commiting them `git stash`
- apply stashed changes to current branch `git stash pop`

### Undo commits
- undo specific commit `git revert [commit id]`
- delete last commit / undo everything up until specified commit `git reset [commit id]`ä
- show commit history and commit ids `git log`

Full git cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
