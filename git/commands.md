# Create new branch from main:
1. change branch  to the other main branch `git checkout MAIN_BRANCH_NAME`
2. pull changes from main branch  `git pull origin MAIN_BRANCH_NAME`
3. create new branch `git checkout -b BRANCH_NAME`

# Pull changes from other branch to the current one
- git pull origin OTHER_BRANCH_NAME(main)
- git status
- check conflicts, if they exist:
  - resolve conflicts
  - git commit -m "Merged OTHER_BRANCH_NAME to CURRENT_BRANCH_NAME"

# Push changes to remote branch:
1. git add FILE_NAME // add file to the commit (git add . -- add all changes)
2. git commit -m "COMMIT_NAME"   <!-- -m - message -->
3. git push origin BRANCH_NAME
