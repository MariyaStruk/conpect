# Create new branch from main:
1. git checkout main  <!--change brunch -->
2. git pull origin main
3. git checkout -b BRANCH_NAME  <!-- create new branch -->

# Push changes to remote branch:
- git add FILE_NAME // add file to the commit (git add . -- add all changes)
- git commit -m "COMMIT_NAME"
- git push origin BRANCH_NAME

# Pull changes from other branch to the current one
- git pull origin OTHER_BRANCH_NAME(main)