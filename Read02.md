
# Git definition
*Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.*
 
 Files in Git can reside in three main states: committed, modified and staged:

- **Committed**
Data is securely stored in a local database

- **Modified**
File has been changed but not committed to the database

- **Staged**
Flagged a file’s changed version 

In order to explain Git, we have to first explain various aspects of Version Control.

## Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

## Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.


## Remote Repositories
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

## Cloned Repositories
As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

These are some of git commands that you will use the most :
* ** git clone** (the link of my repo) : to have my repo downloaded on my local machine, I do this one time
**ACP**: add-commit-push commands I do them regularly
git add . (with space) : when I do some changes on my file I use git add . or instead of . I can add the file name itself, but we use . as a shortcut to stage the changes in all files and folders in my repo
**git commit -m 'the message you want'** (the msg should be between ' ' or " ") : to commit my changes
**git push origin main** : in order to have my changes on GitHub (on the cloud) I use git push origin main,
You will be asked to provide your username and password of your GitHub account (when writing the password you will not see anything)
When I go back to GitHub, I refresh the page and I will see my changes that I added on my files and I can also see my commit messages
**git status:** will give us an explanation about what's happening, the state of our repo, we can see the changes that we did and to see the tracked and untracked files.* 
