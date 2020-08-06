This is my first GitHub repository wherein I simply try to upload my html,css and js files onto a repository on GitHub

To initialize a Git Repository:
1. Open Git Bash
2. Change the Directory to the Folder containing Files that need to be uploaded to GitHub
3. On Git Bash, to Initialize a Repository, execute:
   1.  git init        
4. To view files and folders and check status execute:
   1.  ls -a          
   2.  git status      
5. You can add files to the Repository individually or all at once
   1. To add a file (named "index.html") individually, excute:
      1)  git add index.html
   2. To add all the files at once, execute:
      1) git add .
6. Once added, commit the changes made to the repository by executing:
       1. git commit -m "added files to repo"
7. To check the history of commits, execute:
       1. git log

Uploading the Repository to GitHub
1. Open GitHub on your browser and create your GitHub Account
2. In GitHub click on the "+" button at the top-right corner of the webpage and select New Repository in the Drop-down Menu
3.Name you Repository and add other necessary details. Once done, Click on Create a Repository
4. In the new page that opens, you get 3 options. "push an existing repository from the command line" is our preferred option
5. Under "push an existing repository from the command line" copy the codes one at a time and execute them in Git Bash i,e
   1. First Execute:
       1) git remote add origin https://github.com/Username/Reponame.git
   2. And then execute
       1) git push -u origin master
 6. Reload the page, and there you have your first GitHub Repository!

Branches in Git
A branch is like a different timeline to work on a specific part of the project so that it does not affect the main part of the project

1. To obtain the list of branches, execute:
      1. git branch
2. To create a new branch, execute:
      1. git branch branch1       
3.To return to master branch, execute:
      1.git checkout master
4. To merge a branch to the master branch, execute:
      1. git merge abc
      
Cloning - Downlooading a Repository present on GitHub to your computer
1. On GitHub, go to the Repository you wanted to clone and Copy its URL
2. On your computer, create a new folder. Do NOT clone a Repository inside another Repository
3. Change the directory on Git Bash to your new folder
4. On Git Bash, Execute:
      1. git clone url
You can find the cloned Repository in the New Folder!

      
