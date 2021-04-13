# Git Tutorial: A Comprehensive Guide
![Git](https://codexitos.com/wp-content/uploads/2019/10/blog-What-is-github-and-why-you-should-use-it..png)
* In order to explain Git, we have to first explain various aspects of Version Control.
## Version Control 
* Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
### Local Version Control
* This basically means that Git is a content tracker.
### Centralized Version Control
* So Version Control System helps in handling this by maintaining a history of what changes have happened.
### Distributed Version Control 
*  This means that the code is not just stored in a central server, but the full copy of the code is present in all the developers’ computers. 
## what is Git?
* Git is an Open Source Distributed Version Control System.
### Snapshots 
* Git is a DVCS that stores data in a file system made up of snapshots.
### Local Operations 
* Git mostly relies on local operations because most necessary information can be found in local resources.
### Tracking Changes 
* Change applied to any file or directory is tracked by Git.
### Loss of Data 
* Git is set up to greatly minimize the possibility of irreversible damage to files.
### States
* Files in Git can reside in three main states: committed, modified and staged.
## History of Git
* Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

* [More History](GitHistory.md)
![BitKeeper](https://www.bitkeeper.org/man/BitKeeper_SN_SVC_Blue.png)
![DVCS ](https://miro.medium.com/max/3396/1*gPBljo_uRh-IBtHY2oB7ig.png)
## Getting Started 
### Download Git
* [You can also download Git by visiting this link and following the posted directions for mac:](http://git-scm.com/download/mac)
* [You can also download Git by visiting this link and following the posted directions for windows](http://git-scm.com/download/win)
* [You can also download Git by visiting this link and following the posted directions for Linux](http://git-scm.com/download/linux)
## Initial Customization
* perform some customization steps, which should only need to be completed once on any machine.
### Configuration of Variables
### Identity Setting
### Getting Help
* There are three ways to get more information on a particular command, by accessing the manual:

1. git help command

2. git command --help

3. man git-command

## Setting up a Git Repository
###Importing 
* To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:
1. Switch to the target project’s directory
2. Use the git init command
3. To start tracking these repository files, perform an initial commit by typing the following:
* $ git add *.c
* $ git add LICENSE
* $ git commit -m “any message here”
###Cloning
* By cloning the file, you have copied all versions of all files for a project.
## Workflow
### Local Repository Structure
* The local Git repository has three components:
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
### Saving Changes
* Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
* Untracked files were not in the last snapshot and do not currently reside in the staging area.
### The Life Cycle of File Status
![Image](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
### Check File Status
* To determine the state of files, utilize the git status command: $ git status
### Tracking and Staging a New File
* Track one file only by using the following format: git add filename
* Track all files in a repository by using the following command: $ git add *
### Committing a File
* After staging one or multiple files, you should commit the changes and record what you did within the commit message: $ git commit -m “made change x,y,z”
### Committing All Changes 
* Type : $ git commit -a
### Pushing Changes 
* Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.
### Stashing Changes 
* When you are not ready to commit changes but do not want to lose them either, git stash is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.
