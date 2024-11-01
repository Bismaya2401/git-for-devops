Git Commands Cheat Sheet
1. Git Configuration
Set username:
git config --global user.name "Your Name"
Set email:
git config --global user.email "your.email@example.com"
Check configuration:
git config --list
2. Initialize a Repository
Start a new repository:
git init
Clone a repository:
git clone <repository_url>
3. Basic Workflow
Check status of files:
git status
Add files to staging area:
git add <filename>
or add all files:
git add .
Commit changes:
git commit -m "Commit message"
4. Branching and Merging
Create a new branch:
git branch <branch_name>
Switch to a branch:
git checkout <branch_name>
Create and switch to a new branch:
git checkout -b <branch_name>
Merge a branch:
git merge <branch_name>
Delete a branch:
git branch -d <branch_name>
5. Viewing History
View commit history:
git log
View specific commit details:
git show <commit_hash>
View changes in files:
git diff
6. Undoing Changes
Unstage a file:
git reset <filename>
Undo changes in a file:
git checkout -- <filename>
Revert a commit by creating a new commit:
git revert <commit_hash>
7. Remote Repositories
Add a remote repository:
git remote add origin <repository_url>
Push changes to remote:
git push origin <branch_name>
Pull changes from remote:
git pull origin <branch_name>
Fetch changes from remote without merging:
git fetch origin
8. Stashing
Save changes temporarily:
git stash
View stashes:
git stash list
Apply last stashed change:
git stash apply
Remove last stash:
git stash drop
9. Tags
Create a tag:
git tag <tag_name>
Push a tag to remote:
git push origin <tag_name>
good
