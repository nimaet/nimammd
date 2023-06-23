# Here is a quick start with Git`
# Git Installation
(Git is not the same as GitHub!)
Install git by entering the following in a command prompt:

>> winget install --id Git.Git -e --source winget

or from this link https://github.com/git-for-windows/git/releases/download/v2.41.0.windows.1/Git-2.41.0-64-bit.exe

# Make your local copy of the repository
 The you should make a copy of the repository of your machine. To do so, you open a "Git Bash" by right clicking in a empty folder where you want to keep the files.
 Then, enter the following command in the "Git Bash" you just opened to make an empty repository:
 
 >> git init

Connect to the remote repository

>> git remote add origin https://github.com/nimaet/nimammd.git

Then, make a your local copy by:
 
>>git pull origin master

Now you have a copy of the files on your machine. You can start working on them and once you want to share it with others you should tell the Git to do so.

# Sharing your work

First, you should tell the git to keep the tracke of changes you made. The Git's terminology for this is "commit". Each commit is meant to save a decuctivel amount of change in the project like saving a file. It is advised to include significance of the change you made in a message.

>>git commit -m "a message to indicate what changes you make
 
 Finally, you share it with others by the "push" command:
 
 >>git push origin master
 
 # Here are some resources for further datails about the Git
 https://git-scm.com/book/en/v2
 https://www.youtube.com/watch?v=8JJ101D3knE
 