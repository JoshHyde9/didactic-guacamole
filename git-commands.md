# Git commands

## Objectives

- What is a repository?
- What is GitHub? 
- What is a change?
- What does commit mean? 
- What is a push/pull?
- What are the 3 directories? 
    - Working dir
    - Staging area
    - Local repo


## Commands

- git clone <link>
    - Clones a repo into the current working directory
- git status 
    - Shows the status of the working dir and staging area against the local repo 
    - As well as the local repo against the remote repo 
-  git diff <file>
    - Shows the difference between the working dir and the local repo 
- git add .
    - Move all changes from working tree to staging area
    - use `git add <file/folder>`  to just stage specific files
- git commit -m "my message"
    - Commit staged changes to the local repo
- git push
    - Send all changes to the remote repo 