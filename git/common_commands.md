SETTING UP FOR THE FIRST TIME:
-------------------------------
git config --global user.name [your username]
git config --global user.email [email address]

CREATING A REPO:
-------------------------------
git init - initates a brand new repository on your machine
git add <filename> - for adding new or modified files or directories
git status - make sure we've got everything staged that we want to commit
git diff - to see the exact changes we are about to commit
git commit - to add a snapshot of our progress (don't forget to add a commit message! shortcut git commit -m 'insert commit message here')

CLONING A REPO:
-------------------------------
fork a repo in github.com
git clone https://YourUserName@github.com/User/Project.git (for very old systems) ***OR*** git clone https://github.com/User/Project.git (for newer systems) ***OR*** set up ssh and use git@github.com:User/Project.git

CONTRIBUTING TO A REPO:
-------------------------------
fork & clone
change, add, commit locally
git push origin master
in github, click "submit pull request"

INVESTIGATION & OTHER COMMANDS:
-------------------------------

git help [command name]
git [command name] --help
man git-[command name]

git rm [file]
git tag [tag name]

git branch (current branch indicated by *)
git checkout [branch-name]
git checkout -b [branch-name] (create a new branch and move to it)
git branch -d [branch-name] (delete a branch)

