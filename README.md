git init to initialize Git in terminal

=======================
__Three Stages of Git__
=======================

# Working Directory
    -Everything that is not saved lives here
    -Area where all of our files and directories and changes ar living all the time

# Staging Area
    -Stage fixes into staging area in order to get ready to commit them
    -Files and directories that we explicitly add to the staging area
    -Use git add <filename> to get file from working directory to staging area

# .git Repository
    -Commit to this to save it
    -here all our snapshots are stored
    -git commit -m "MESSAGE HERE" to commit something to the .git repository and add a   message


Use git status to check on the files and their placement within the Git stages

# Adding multiple files with same file type
    - git add *.filetype where * is a wild card and filetype is something like "html" or    "css"

# To create a hidden file, add a . before the file name ".hidden.txt"

# To add all files to staging area, use git add -A

# Add files that you want git to ignore to .gitignore

================
__Git Branches__
================

          /--0-------0----0 > can mess around with code without affecting master branch
         /               /  > you can merge the two if you like the second branch
0-------0----0----0-----0   > Master branch

# List all branches
    - git branch

# Adding a branch

# Changing branches

# Merging a branch

# Removing a branch