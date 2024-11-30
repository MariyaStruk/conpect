# Create new branch from main:
1. git checkout main  <!--change brunch -->
2. git pull origin main
3. git checkout -b BRANCH_NAME  <!-- create new branch -->

# Push changes to remote branch:
1. git add FILE_NAME // add file to the commit (git add . -- add all changes)
2. git commit -m "COMMIT_NAME"   <!-- -m - message -->
3. git push origin BRANCH_NAME

# Pull changes from other branch to the current one
- git pull origin OTHER_BRANCH_NAME(main)