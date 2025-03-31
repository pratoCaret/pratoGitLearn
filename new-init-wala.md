this is to check ki konsi file upload hori hai

git command used is as follows:
1. git init - create the local repo 
    git branch -m 'branch-3'
2. git checkout -b <branch name>
3. git remote add origin <git ssh> - in the folder I want to upload through terminal.
4. git branch --set-upstream-to=origin/deskto-git-branch
5. git add .
6. git commit -m "comment"
7. git push origin desktop-git-branch


future workflow:
git add .
git commit -m "Updated files"
git push origin desktop-git-branch
