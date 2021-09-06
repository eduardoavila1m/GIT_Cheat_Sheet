# GIT_Cheat_Sheet

## Create a repository from local machine

This sections shows the workflow to create an online repository from local machine 

### Initialize GIT Repository

    git init -b main

### Add files

Stage all files (that are not listed in the .gitignore) in the entire repository

    sudo git add .
    
### Commit

Record changes to the local repository

    sudo git commit -m "First Commit"

### Branch to Origin

    git branch -M main
        
### Add Origin Path

    git remote add origin <Path to repository https://github.com/....>

### Create a read me file


    echo "# New Repository" >> README.md

### Add files
        
    git add README.md        

### Commit

    git commit -m "created README.md file"

### Push to Cloud Repository

    git push -u origin main

## Upload changes to cloud

This section shows a workflow to upload changes to the online repository

### Check Repository Status
Navigate to the folder of the repository. Make sure that the ".git" folder exists with the command line command

    ls -a
    sudo git status
    
### Add files

Stage all files (that are not listed in the .gitignore) in the entire repository

    sudo git add .
    
### Commit

Record changes to the local repository

    sudo git commit -m "message that commits"
    
### PUSH

Update the remote refs along with associated objects

    git push
