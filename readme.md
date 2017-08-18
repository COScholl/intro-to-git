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

# practice exercises 2
- create new dir (git_section_3)
- change dir to git_section_3
- git init
- create 3 new files using touch: file1.txt, file2.html, file3.js
- create new dir called random_files
- move .txt and .js to random_files dir
- git status
- remove .js file from staging area
- create 3 new files in random_files dir (file4.css, file5.css, file6.js)
- git status
- add all .js to staging area
- cd .. and mkdir secret_stuff
- in secret_stuff, touch file1.yml and file2.js
- create .gitignore to ignore secret_stuff
- git status
- add .gitignore to staging area- commit changes

# Git branches
- Listing all branches: git branch
- Adding a Branch: git checkout -b <branch_name>
- Changing branches: git checkout <branch_name>
- Merging a branch: git merge <branch_name> (merge current branch into <branch_name>)
- Removing a branch: best not to delete branches, however:
  command: git branch -d <branch_name>
