### clone 
git clone
git clone https://github.com/Rezashatery/git-commands-essentials.git

### Go to the folder for changes
cd git-commands-essentials

### Shows what are in the folder 
la -la

### show the status of everything has done such as update, delete and add files or folder
git status
when add some files and still does not add in the git after using this command the git tells that:
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        commands.md

### add files to the git
gid add .
this dot means that you add all the files that you have either you add recently or you added before to save the changes.


### commit files to the git 

git commit -m "added command.md" -m "add description in here"

-m is for message and you have to have a message for commiting in order to for example what and why you do somehting in your file. the second -m is for the description 

this command is not upload in your github.

### push(upload) files to the git (remote repository)

<<<<<<< HEAD
=======
git push origin 

to upload everything in yout repository

### uplaid in new branch
>>>>>>> dc7189d0606e47693fa6a2e934c5714b831bd3ef
