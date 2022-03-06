# test1
testing git functionality


GitHub Commands



-----------------------------------------------------------------------
General
ls - lists all files/folders in a folder
clear - clears terminal info
git init - Initialize Repository (new folder)
git Status - Status of git folder
git log - History of commits



Create New Repository
Create new on github website
copy HTTP link for new repository
open gitbash terminal

git clone <HTTPS Link>
click "yes" for connecting this folder


or for starting in the folder on your computer with files you already want to push 
git init
git add .
git status
git commit -m "First Commit"
git remote add origin <HTTPS Link>
git push -u origin master
<username/password>



-----------------------------------------------------------------------
Commit Files (2 step process)
git add <FILE>    or     git add . (adds all files in folder)
git commit -m "Commit Message"
git push



-----------------------------------------------------------------------
Use Historical/Previous versions of files
git checkout <commit-hash>


-----------------------------------------------------------------------
Creating a new Branch
git branch <new-branch-name>

branch name = "master" can get back to the latest/greatest version

-----------------------------------------------------------------------
Merge in changes
git merge <branch-name>
