# GIT_Cheat_Sheet

THis document shows a workflow to upload changes to the online repository

## Check Repository Status
Navigate to the folder of the repository. Make sure that the ".git" folder exists with the command line command

    ls -a
    sudo git status
    
## Add files

Stage all files (that are not listed in the .gitignore) in the entire repository

    sudo git add .
    
## Commit

Record changes to the local repository

    sudo git commit -m "message that commits"
