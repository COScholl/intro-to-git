# Working dir
-area where files, dirs and changes are living all of the time

# Staging area
-files and dirs that are explicitly added to staging area
- command git add <filename>: to add file to staging area
- command git rm --cached <filename>: to unstage

# Git Repository
-where snapshots are stored
- command git commit: creates key and logs changes with message
- command git log: to see the history of commits

# Practice exercises
- Create new dir
- Change dirs into project folder
- Init a git repository to begin tracking project
- Create files for project (index.html, style.css)
- Check status of repository
- Add the files to staging area
- Check status again
- Commit files to repository

# Add multiple files of a certain type
- command git add *.<filetype>
- adds files with same filetype (.html, .txt, .css, etc)

# Add all files in a dir (including hidden)
- command: git add -Add
- adds all files and folders from current dir

# Removing files
- git reset HEAD <file>: to unstage from staging area (unstage from files added)

# Ignoring files
- create .gitignore file and add file2.txt to the doc.
- git status no longer sees file added to .gitignore


