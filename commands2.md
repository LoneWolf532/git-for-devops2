# Setting Up Git
git init
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Basic File Operations
touch filename.txt
cat filename.txt
rm filename.txt

# Viewing File and Repository Status
ls -a
git status
git log

# Staging and Committing Changes
git add filename.txt
git rm --cached filename.txt
git commit -m "Commit message"

# Working with Branches
git branch
git checkout -b branch_name
git checkout branch_name
git branch -d branch_name

# Restoring Changes
git restore filename.txt
git restore --staged filename.txt

# Viewing Logs and History
git log
git show commit_id

# Configuration Changes
git config user.name "NewName"
git config user.email "new.email@example.com"

