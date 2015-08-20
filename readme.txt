This is the first file in the Git Repository.
--------------------------------------------------

1. In order to create a repository navigate with the CMD to the folder of the 
project and run "git init" command.

2. In order to check the status of a file inside the project folder type 
"git status". This command will show the overall status of all the files
in the project folder.

3. To add a changed file to the repository type "git add <FILENAME>". To add
all files at once type "git add.". To commit a file or folder to the repository type "git commit -m <your message>".
Than you can see the differences with "git diff". To end that command type q or less.

4. To add remote connections type "git remote add <REMOTENAME> <URL>". This means
you have to create a repository on git and than link your local to the remote one
the remote name can be anything but should ideally be identic to the project.
To set the URL to the remote (the server of GIT) type "git remote set-url <REMOTENAME> <URL>".

5. To push the changes of the local repository to the remote (the GIT server) type
"git push <REMOTENAME> <BRANCH>". Normally the BRANCH at the beginning of a project is "master".

6. To create and switch to a branch type the following command "git checkout -b <BRANCHNAME>", which 
will create a new branch in the current fork or project and switches to it. With the command
"git branch", it's possible to list the current branches. To rename a branch where you are currently working
on you can type "git branch -m <NEWBRANCHNAME>".

7. To see the current working directory or branch in git type "git status".

8. In order to update changes made to a remote branch use the following command "git pull <REMOTENAME> <REMOTEBRANCH>".
You can also view the changes before you pull them into your repository by typing
"git fetch --dry-run".

9. To merge a branch into the current branch which you are working on type "git merge <BRANCHNAME>". To change the 
branch you are currently working on you have to type "git checkout <BRANCHNAME>".

10. To delete a local branch you can use the following command "git branch -d <BRANCHNAME>". This will delete the
local branch you are currently working on.
To delete a remote branch you have to use this command "git push <REMOTENAME> --delete <BRANCHNAME>" and in order to 
pull from that remote branch you type "git pull <REMOTENAME> <BRANCHNAME>".