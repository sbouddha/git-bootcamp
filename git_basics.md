To download a file from a GitHub repository, make changes to it, and push the changes back, you can follow these steps:  
1. Clone the repository to your local machine using the git clone command. For example, to clone a repository named "my-repo" owned by the user "my-user", you can run the following command in your terminal:
```
git clone https://github.com/sbouddha/sql-100-days.git
```

2. Navigate to the cloned repository using the cd command:
```
sql-100-days
```

3. Find the file you want to modify and make the necessary changes using your preferred text editor.  
   
4. Stage the changes using the git add command. For example, to stage all changes made to files in the repository, you can run:
```
git add .
```

5. Commit the changes using the git commit command. For example, to commit the changes with a message "Update file.txt", you can run:
```
git commit -m "Update file.txt"
```

6. Push the changes back to the repository using the git push command. For example, to push the changes to the "main" branch of the repository, you can run:
```
git push origin master
```

Note that you may need to authenticate with your GitHub username and password or access token to push the changes.

---
if you need to setup new folder for the github:

echo "# git-bootcamp" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/sbouddha/git-bootcamp.git
git push -u origin master