# Check the current version
git --version\

# Configuration
git config --global user.name 'John Smith'
git config --global user.email 'john.smith@email.com'

# Initialize Local Git Repo
git init

# Creating a file
git touch file

# FIles to be ignored
Add files or directories to .gitignore that you wish to ignore.
e.g. File Name, /directory name

# Adding files
git add file
git add *.txt
git add .

# Check the current status
git status

# Commit changes
git commit
//-- i for insert model
//-- Esc to exit insert model
//-- :wq
git commit -m 'description for the commit'

# Cloning a remote repository onto your machine
git clone https://github.com/davidgreavesau/GitNotes.git

# Push to the remote repository
git push

# Pull the latest changes from the remote repository
git pull

# Branches
git branch <name of branch>

