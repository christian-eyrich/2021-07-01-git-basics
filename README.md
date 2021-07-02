# 2021-07-01: Git Basics 

- `git init`: initialize git repository in current working directory
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: creates a commit, you provide message

- `git log`: shows you the log of your commits 
  - `git log --online`: shows you the one line version of the log

- `HEAD`: where you currently are (the version of the files on your computer
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
  - `git diff <HASH> <FILE>`: compares curretn file to <HASH> version

- Use `git status` to help you find commands to unstage or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>
  - if you run `git checkout <HASH>` without the <FILE>
  - You can fix this by running `git checkout main`


- git ignores empty folders
- use .gitkeep to keep a folder
- use .gitignore to ignore files

# REMOTES 

- `ssh-keygen`: to create a ssh key
- `git remote add <URL>`: adds the url
- `git push origin main`: push to the main branch to the orgin remote
- `git pull origin main`: pull to the remote site
 
# main 
