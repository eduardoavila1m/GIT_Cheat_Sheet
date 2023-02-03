# GIT_Cheat_Sheet

## Install GIT in your local machine.

    Follow the instruction in the GIT website to install GIT locally.

## Review GIT version 

If git has already been installed. review the git version with the command below

    git version
    
## Update GIT

To update git to the most recent version run the command below.

    git update-git-for-windows

## Create a repository from local machine

This sections shows the workflow to create an online repository from local machine. For this to work is important to first create an empty repository that is either public or private via the browser and github website.

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

### Create a new repository in the Github website

When creating the repository in github first navigate to your github account in a web browser. Make sure to choose a proper name with no space character, is better to use underscore. Check the sharing properties (eg. private, public), the type of Licence to release the code and other specifications provided in the repository creation wizard. Once the new repository has been created. Copy the link.

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
