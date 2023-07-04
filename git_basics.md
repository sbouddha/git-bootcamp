**Install VSCode from Official website**  
Link : https://code.visualstudio.com/

**To Check if GIT is installed on your machine**  
Execute this command in GIT Bash or VSCode Terminal  
```bash
git --version
```
If GIT is not installed, install from official website. Link : https://git-scm.com/downloads
and then check above command to get the git version in Git Bash.

**This will initialize current directory as a git repository**
```bash
git init
```
Note : If you do not put any parameter in above command, it will take current directory as default, else, you can pass a folder name so that that folder can be made a Git repository.

```bash
git init sql-100-days
```
it means sql-100-days will be the folder which will become a Git repository.

**To Initialize default branch (master or main etc.)**  
```bash
git config --global init.defaultBranch master
```

**To to the git repo folder**
```bash
cd sql-100-days
```

**Rename the current branch to master/main or some other**
```bash
git branch -m master
```
The command `git branch -m master` renames the current branch to "master". This command is used to rename the current branch to a new name, in this case, "master". 
This command is useful when you want to rename a branch to a more descriptive name or to follow a new naming convention.   
After running this command, you can push the changes to the remote repository using the `git push -u origin master` command. 

**Check if the folder is made Git Repo or not**
```bash
ls -la
```
here `a` is for listing hidden files/folders.

You should see a .git folder, which means now this folder is now a GIT repository.
Also, you can do below :
``` bash
git status
```
and it will show in which branch you are currently on.  

**Important Note**  
It is highly recommended that you do not directly commit or push changes to the master/main branch of your repository. The master/main branch is typically reserved for stable and production-ready code. Directly committing to this branch can introduce errors and disrupt the workflow for other contributors.

Instead, follow the best practice of creating feature branches or topic branches for your development work. This allows you to work on your changes independently and collaborate with others without affecting the main branch. Once your changes are complete and tested, you can submit a pull request or merge request to propose your changes for review and integration into the main branch.

By adhering to this approach, you ensure that the main branch remains stable and only contains validated and approved changes. It also promotes a smoother and more organized collaboration process among team members.

