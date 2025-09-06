# event-flyer
fCC Absolute and Relative Units Lab.
Practice a "branch workflow"

git "feature branch management" website homepage build

New Project Workflow:

create a repo at GitHub with a README file. (use the root directory name of the project)
copy the SSH key to the clipboard
create the root directory of the project in Terminal. cd into the new directory.
git clone the ssh key. cd into the cloned directory. (it should have the README file listed)setup the basic new project directory hierarchy.
open code editor and write out the project synopsis in the README file
open Terminal in the code editor

git add . (git status at any time to verify) 
git commit -m "USEFUL MESSAGE TO THE DEV TEAM" 
git push origin main 

go to GitHub and verify push

'Feature/Branch' of an existing project Workflow:

git pull 
git checkout -b feature/branch name 
code .

work on project

git add . 
git commit -m 'DEV MESSAGE' 
git push -u feature/branch name

open gitHub, click 'compare pull request'
review each time and click: 
'create pull request', 'merge pull request", 'confirm'
delete branch if you want. if you don't. will the pull come from branch un-deleted or from main?'

git status in Terminal to check for outstanding commits