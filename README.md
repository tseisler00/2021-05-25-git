# 2021-05-25 git 

- `git init`: is intialize git repo in current locaiton
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: commits files from the staging area
    - `git commit -m "MESSAGE"`: comit without opening editor
- `git log`: show you commit history
    - `git log --oneline`: condensed history

- `git diff`: gives you the difference
    - `git diff --staged`: diff files in the staging area

- `git diff HEAD~2`: diff 2 commits ago
- `git diff <SHA> <FILE>`: diff a file against a specific commit

- `git checkout <SHA> <FILE>`: revert <FILE> frm <SHA> to current
- `git checkout <SHA>`: move you to <SHA>
     - `git checkout main`: go back to main starting point

- `.gitignore`: file that pattern  matches files to ignore
- `.gitkeep`: convention to keep an empty folder
