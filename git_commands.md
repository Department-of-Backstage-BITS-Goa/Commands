# Git and GitHub Commands
Git & GitHub
Important Commands

## Initialising Repository:- 
Initialise Repository - git init

## Staging:- 
* Stage a Folder/ Change in a Folder in Project Folder - git add “Folder Name”
* Stage all Folders - git add .

## Commits Handling:-
* Commit Staged Changes - git commit -m “Commit Message”
* Display all commits - git log
* Display each commit in one line - git log -oneline
* Check Out previous version - git checkout <commit_code_from git log> 
* Go back to master - git checkout master/required_branch
* Change to old version - git revert <commit_code>
* Change permanently to old version without removing changes of current commit - git reset <commit_code>
* Change permanently to old version removing changes of current commit - git reset <commit_code> --hard

## Branch Handling:-
* Create new branch - git branch <branch_name>
* See all branches - git branch -a
* Switch branch - git checkout <branch_name> 
* Create and Switch to new branch - git checkout -b <branch_name>
* Delete branch before merging- git branch -D <branch_name>
* Delete branch after merging- git branch -d <branch_name>
* Merge into another branch(current working branch must be this branch) - git merge <branch to be merged>
* Incase of conflicts you can fix the code as per your wish after the above command

## Remote Repository:- 
* Storing Remote Repository under Alias - git remote add <alias_name, usually_”origin”> ‘<Repository Link>’
* Storing Alias of Remote Repository under an Account of different user?/Organisation -  git remote set-url <alias_name> “https://YOUR_GITHUB_USER@ ‘<Repository Link>’”
* Push current repository to remote repository - git push -u origin master
* Clone a remotes Repository - git clone ‘’Repository Link”

## Social Coding:-
* Merge remote repository with changes with current repository - git pull origin master
