# Git-GitHub-Notes
Commands for Git and GitHub

Git - "Version Control System" that helps to track changes in code.

Two main purposes of Git and GitHub are:
    1. Track the History
    2. Collaborate
    
GitHub - website that allows developers to store and manage their codes using Git.

git --version # gives the current version of git on your system

Configuring Git:
    git config --global user.name "My Name"
    git config --global user.email "someone@gmail.com"

Clone - clone a repository on our local machine # remote[GitHub] to local[PC]
    git clone <link>
    
Status - displays the state of the code
    git status
    
Untracked - new files that git doesn't yet track

Modified - changed

Staged - file is ready to be commited

Unmodified - unchanged

Add - adds new or changed in your working directory to the git staging area
    git add <file-name> or git add .

Commit - it is the record of change
    git commit -m "some message"

Push - upload local repo content onto remote repo
    git push origin main 

