1. Create and switch to sub-branch
    - git checkout -b sub-branch

2. Wwitch to sub-branch -> when the sub-branch has been created
    - git checkout sub-branch
<!--
make some changes to the file, then run the nex
commend git add some_file.py  # or use 'git add .'
-->

3. Make edits, then add specific files or all changes
    - git add some_file.py  # or use 'git add .'

4. Commit the changes with a message
    - git commit -m 'file updated'

5. Push the sub-branch to the remote repository
    - git push -u origin sub-branch

6. Switch back to main branch
    - git checkout main

7. Merge sub-branch into main
    - git merge sub-branch

8. Push the changes in main to the remote repository
    - git push -u origin main


# UPDATED VERSION
# Here’s a brief validation of your original steps:

1. Create and switch to a sub-branch:
    - git checkout -b sub-branch

2. Edit files, stage changes:
    - git add some_file.py or git add .

3. Commit the changes:
    - git commit -m 'file updated'

4. Push the changes to the remote sub-branch:
    - git push -u origin sub-branch

5. Exit the sub-branch and switch back to main:
    - git checkout main

6. Merge the sub-branch into main:
    - git merge sub-branch

7. Push the updated main branch to the remote:
    - git push -u origin main

# See current branch you are in
    - git branch -> branch with * asterik is where you are in.

# Delete sub-branch
    - git branch -d sub-branch -> delete sub-branch after merging
    - git branch -D sub-branch -> delete sub-branch without merging