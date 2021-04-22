# First part - command line

 mkdir name is used to create a folder with the name name
 
 mkdir folder\subfolder\subsubfolder is used to create folders with the hierarchy, meaning one inside the other
 
 It is important to note that you can create multiple folders in the same line
 
 rmdir name is used to remove the directory named name. 
 
 As a note, it is possible to use a /s flag to delete a directory that has nested files and subdirectories
 
 cd allows you to change directories

 cd foldername allows you to go directly to the folder called foldername

 cd foldername\subfoldername is useful to go directly to the subfolder

 cd.. takes you one folder up

 d: allows to change the drive

 dir lets you know which directory you are in

 ren oldname newname makes the folder oldname change its name to newname

 copy location\filename.extension newlocation\newname.extension allows to copy files from one location to another, and you can change the extension

 xcopy /s /i d:\foldername c:\otherfolder would copy the file using /s to copy all subfiles that have content

 del*.extension – deletes all files with the extension

 del example*.* – deletes all files beginning with example 

 del *.* – deletes all files

 app.exe would let you open an app if you are in the folder where it is located

 help makes useful commands appear

 help command \? gives you more details on the command 

 git diff compares two archives

 nano name.extension creates an archive named name with the specified extension

 git status gives you the status of the computer

 
# Second part: Git

 git config --global user.name "example.username"

 git config --global user.email "example@dominio.end"

 git config --global core.editors nameoftheeditor defines which editor to use

 git config--list lets you check your configurations

 git init is used to start a repository in your computer

 git nano filename.extension creates a file named file name with the especified extension and lets you type it,
 you would use ctrl+x to leave, y to save and then enter

 git add filename.extension adds it to start tracking it

 git commit "this is the commit" lets you commit it

 git push is used to upload 

 git clone https://github.com/example is used if you want to clone a directory

 cat .gitignore *.[extension] *~ is used to tell git to ignore files with that extension and the second to ignore files ending with the symbol

 git diff gives the difference between files

 git rm filename.extension removes the file 

 git log allows to see the history

 git remote -v lets you see the remotes that are associated

 git checkout -b branchname switches to a branch
 
 git merge otherbranch to merge them

 git branch -d example is used to delete the branch example

 git mergetool is used as a graphic tool so see merging problems and resolve them

 git commit would let you finally commit the merge

 git flow init initiates gitflow

 git flow feature start feature/example creates a new feature

 git flow feature publish feature/example publishes it from the remote desk

 git flow feature pull origin feature/example is used to obtain a feature branch from the remote repository

 git flow feature track feature/example to start tracking it

 git flow release start release--0.1 starts the release 0.1

 git flow release finish release--0.1 finishes the release

 git flow publish release--0.1 publishes the release

 git flow hotfix start hotfix--0.2 creates a hotfix

 git flow hotfix finish hotfix--0.2 would finish it

 
