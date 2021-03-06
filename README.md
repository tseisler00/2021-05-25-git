# 2021-05-25 Git Basics

- `git init`: is intialize git repo in current locaiton
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: commits files from the staging area
    - `git commit -m "MESSAGE"`: commit without opening editor
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

## Remotes

- `git remote add <NAME> <URL>`: point to the rmeote url. <NAME> is usually "origin"
- `git push <WHERE> <WHAT>`: local repo -> remote
- `git pull <WHERE> <WHAT>`: remote -> local 
 
## BRANCHES

How to rename "master" to "main"
 
1. `git checkut -b main`
2. fix default branch in github
3. `git push origin main`

