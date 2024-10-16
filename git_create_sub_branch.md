# Create and switch to sub-branch
git checkout -b sub-branch


<!--
make some changes to the file, then run the nex
commend git add some_file.py  # or use 'git add .'
-->

# Make edits, then add specific files or all changes
git add some_file.py  # or use 'git add .'

# Commit the changes with a message
git commit -m 'file updated'

# Push the sub-branch to the remote repository
git push -u origin sub-branch

# Switch back to main branch
git checkout main

# Merge sub-branch into main
git merge sub-branch

# Push the changes in main to the remote repository
git push -u origin main


# UPDATED VERSION
# Here’s a brief validation of your original steps:

# Create and switch to a sub-branch:
git checkout -b sub-branch

# Edit files, stage changes:
git add some_file.py or git add .

# Commit the changes:
git commit -m 'file updated'

# Push the changes to the remote sub-branch:
git push -u origin sub-branch

# Exit the sub-branch and switch back to main:
git checkout main

# Merge the sub-branch into main:
git merge sub-branch

# Push the updated main branch to the remote:
git push -u origin main


# See current branch you are in
git branch -> branch with * asterik is where you are in.

# Delete sub-branch
git branch -d sub-branch -> delete sub-branch after merging
git branch -D sub-branch -> delete sub-branch without merging