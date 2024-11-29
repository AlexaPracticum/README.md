TERMINAL COMMANDS:

( pwd ) - check current location 

( ls ) - show what is in the folder 

( cd ) - move to <folder_name> 

( cd .. ) - move back 


( mkdir ) - create new folder   [ eg: mkdir dev ]

( touch ) - create new file   [ eg: touch hello-world.txt ]

( mv ) - rename  [ eg: mv hello-world.txt HelloWorld.txt ] / move file [ eg: mv HelloWorld.txt temp ] 

( rm ) - delete file [ eg: rm HelloWorld.txt ] 

( rmdir ) - delete folder [ eg: rmdir temp ]   // Only if it is empty 

( rm -r ) - force delete folder [ eg: rm -r temp ]   // Will be deleted with all it contains


( echo ) - print message on screen [ eg: echo “Hello, world” ] 

( echo >> ) - print message INTO file [ eg: echo “Hello, world” >> HelloWorld.txt ] 

( cat ) - print file containments on screen [ eg: cat HelloWorld.txt ] 


GIT SET UP:

( git —version ) - check installation status of git and its current version 

( git config —global user.name “UserName ) - set username

( git config —global user.email useremail@email ) - set email

( git config —list ) - pull up set settings

( git config —global core.ignorecase false ) - set case sensitivity 

( git init ) - make folder a Git repository (repo)

( rm -rf .git ) - make folder no longer a Git repository 

( git status ) - check git status of folder

( git add / git add —all / git add . ) - add to git folder [ eg: git add hello.txt ] 

( git commit -m ‘My first commit’ ) - save new version of file in repository 


Add repository to GitHub:

1 . ( git remote add origin git@github.com:<ВАШ НИКНЕЙМ>/first-project-git.git ) - add file remotely to GitHub

2. ( git branch -M main ) - makes the branch main

3. ( git push -u origin main / git push ) - transfer changes in local branch to remote repository GitHub

( git pull ) - get access to changes and contant from a copy file


Working with Git branches:
( git branch ) - check current branch 

( git branch <new_branch> ) - create new branch 

( git checkout <branch_name> ) - moving from branch to branch  

( git checkout -b <another_branch_name> ) = ( git branch <new_branch> ) + ( git checkout <branch_name> )

( git merge new_branch ) - must be done from the branch with which the other branch is merged
