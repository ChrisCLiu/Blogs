# Learning Git in Ubuntu #

### What is Git? ###
Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. [Git-Wikipedia](https://en.wikipedia.org/wiki/Git)

### Why Git? ###
- Easily to use and corporate between multiple users
- A better way to backup and track versions of files.
- A good repository to maintain code works. 
 
### Install Git in Ubuntu 16.04 ###

```
$ sudo apt-get install git
```
For users, configuration is needed.

```
$ git config --global user.name "YourName"
$ git config --global user.email address@example.com
```

### Local Git operations ###
1. ```git init```
Create an empty git repository in current folder. Save file changes in the **./.git/** folder. 

2. ```git add```
Add changes in current folder to the index of git.  
    ```git add dir```   (Add directory dir to the index of git);  
    ```git add fil```   (Add file fil to the index of git);  
    ```git add . ```    (Add all files/directories in this folder to the index of git).  

3. ```git commit```
Commit the changes in the index of git.  
When commit changes to github.com, comment is compulsory.  Use command like ```git commit -m "comments"```
