# Cheat Sheet for Terminal

## Basic Commands
---
To see which directory you are in, use.
```
pwd
```

To find what is in our directory, use.
```
# For basic information
ls 
# For a detailed list 
ls -l
# For a detailed list and the hidden folders
```


To change the directory to Documents,
```
cd Documents
```

To go back to the home directory
```
cd
```
---
## Files and Folders
---
To make a new directory within the current directory .
```
mkdir name_of_dipository
```

To create a file, remember to include the file type.
```
touch file.txt
touch file.md
```

To open a directory in vscode to show all the files.
```
code .
```

To move a file from current directory to another directory, such as Documents.
```
mv file.txt ~/Documents
```
 To rename a file name.
 ```
mv file.txt renamed_file.txt
```

To delete a file. 
```
rm file.txt
```
But to delete a directory.
```
rm -r
```
Another command to delete without needing permission. NEVER USE.
```
rm -rf
```
---
## Extra Stuff
---
To see all the commends that have been used in the terminal since being openend.
```
history 
```

---
## Git 
---

To initiate Git repository in a directory, go into the directory and use.
```
git init
```
 To see the state of the working directory.
 ```
 git status
 ```
To add a changes to a file and subsequently commit it.
```
git add file.txt
git commit -m "Just adding update"
```
To make further changes and update with the current directory.
```
git add .
git command -m "Even newer update"
```
 To see the history of the commits.
 ```
 git log
 ```

To add the local repository to github. Get the ssh link from github repository.
```
git remote add origin url_here
```
Now that the repositories are linked. To upload from computor to github use.
```
git push origin main
```
To clone a repository from github to computer use.
```
git clone repository_url
```
To download changes from a repository.
```
git pull origin main
```


