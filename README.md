# git

⭐ Git Notes
📌 What is Git?
Git is a Distributed Version Control System (DVCS) used for tracking changes in source code.

✅ Git Helps You:

Track changes (who, when, why)

Restore previous versions

Work safely in teams

Manage multiple versions

Works on Linux, Windows, macOS

📌 Three Key Areas in Git
1️⃣ Working Directory

Where files are created/modified.
Files here are untracked until added.

2️⃣ Staging Area

Files moved to staging using:

git add <filename>


These files are ready for commit.

3️⃣ Repository

Contains final committed code with complete history.

📌 Basic Setup
✔ Install Git
yum install git -y

✔ Check Git Version
git -v

📌 Initialize Git Repository
mkdir foldername
cd foldername
git init

📌 Working With Files
✔ Create a File
touch filename

✔ Check Status
git status

✔ Track a File
git add filename

✔ Track ALL Files
git add .

✔ Commit Files
git commit -m "message"

📌 Viewing History
git log
git log -2
git log --oneline
git show <commit-id>

📌 .gitignore

Create/edit:

vim .gitignore


📌 Untracking a File
git rm --cached filename

📌 Configure Git
git config user.name "your name"
git config user.email "youremail@gmail.com"

📌 Add Multiple Files
git add file1 file2 file3
git add .

📌 Reset in Git
🔸 Soft Reset (keeps changes)
git reset --soft HEAD~1

🔸 Hard Reset (removes changes)
git reset --hard HEAD~1

🔸 View Deleted Commits
git reflog

📌 Revert (Undo Safely)
git revert <commit-id>

📌 Cherry-Pick
git cherry-pick <commit-id>

📌 Amend Commit
git commit --amend -m "new message"
git commit --amend --author="Name <email>"

📌 Restore
git restore filename

📌 Stash Commands
git stash
git stash list
git stash apply
git stash clear

📌 Branching
git branch branchname
git checkout branchname
git checkout -b branchname
git branch -d branchname
git branch -D branchname
git branch -m oldname newname

📌 Merging Branches
git checkout master
git merge dev
#adding some data on it


