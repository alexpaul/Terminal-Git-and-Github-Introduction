# Terminal-Git-and-Github-Introduction

## Objective

* Introduction to Terminal, Git and Github   

## Terminal 

* cd ~/Documents - navigating through directories   
* pwd - present working directory   
* ls - list contents of current directory  
* ls -a - show hidden files in current directory  
* mkdir "directory/folder name" - create a folder  
* cd "directory name"   
* echo "Terminal Introduction" >> README.md - creates a file with markdown extension    
* touch "filename.extension" - also creates a file   
* open "filename" - opens up that file for editing    
* rm "filename" - delete file from filesystem    
* rm -rf "folder name" - delete a folder from the file system   



## vi - Visual Editor 

[vi resource](https://www.washington.edu/computing/unix/vi.html)   

* vi "filename" - opens filename is already exist or creates the filename and opens up the editor   
* esc - command mode   
* i - insert mode (here you can edit your file)   
* :w - save the file (you need to be in command mode)   
* :wq - save the file and exit vi   


## Git 

* git init - create a local git repository   
* git status - monitor changes in the staging area   
* git add "filename" - add "filename" to the staging area   
* git commit -m "initial commit" - add a message to the commit   
* git remote add origin <repo url> - create a handle to the remote repo   
* git push --set upstream origin master - set the remote upstream   
* git push - push changes to the remote branch   
* git pull - get the latest updates from the remote branch   
* git clone - copy a clone to your local machine    


## Github 

signup for a [Github](https://github.com) account  

## Reading Resources

* [github cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)   
* [github hello-world starter resource](https://guides.github.com/activities/hello-world)   
* [Getting started with UNIX](https://gist.github.com/alexpaul/8718808a32c30bdfa91cd33fc31f1f58)


#### Storing your github credentials in Terminal

$ git config --global user.name "your username"   
$ git config --global user.password "your password"
