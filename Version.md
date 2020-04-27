# Version Control

![](https://images.ctfassets.net/vfzqbr9skrdg/3EpcFkGyOZhpgIqWVOWNWp/187ae333642f01d59f938f991e1ab516/git.svg)

###### Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes so we can revert the file we want to a previous project.

###### There some thing called Local version control and use your hard deskwhere there Centralized Version Control System CVCS This system entails a single server storing all changes and file versions, which can be accessed by various clients.
###### where the  Distributed Version Control systems DVCS which make the server as a single point of failure.and to prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories.

## What is Git

Simply is DVCS which can store data in a file system and each time we made change or commit **Git** creates a snapshot of the file and stores a reference to it.

### Git can track changes and can minimize loss of data. And the files can be reside in three main states: committed, modified and staged.

# History of Git
Its starts with 2002 with DVCS Bitkeeper then the devlopers stoped to use DVCS due to tension between the Linux kernel community and the company behind BitKeeper. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

### Working on Git

First you need to specify yor operating system, if you are working on Windows you need to download [Git](http://git-scm.com/download/win)
Then you need to [download Git](http://windows.github.com) Then you need to mount it to your Terminal.

And Git have Graphical Clients you can access it [Here](https://git-scm.com/downloads/guis)
### Initial Customization
After making sure Git has been installed, you should perform some customization steps.
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.
It can be done by 
**git config --global user.name "MohammedGHafri"**

**git config --global user.email **"eng.m.ghafri@gmail.com"**

To confirm that you have the correct settings, enter the following command:
git config --global user.name and it should return MohammedGHafri.
git config --global user.email and should return eng.m.ghafri@gmail.com.

## **Setting up a Git Repository**
1. cd (any directory)
2. git init
3. git add *.c
4. git add LICENSE
5. git commit -m “ your message ”

6. clone URL
9. code .
7. git status
8. git add filename
9. git commit -m "new line"
10. git push origin master


## WorkFlow

![](https://www.udemy.com/blog/wp-content/uploads/2015/08/image006.png)

## Remote Repositories
Teams can use remote repositories to push information to and pull data from.
Git will give "origin" to the server from which you cloned and the name “master” to your local branch.
You can **see** yor Remotes by command **Git remote**, it will view the short name such as origins and by using git remote -v, you can view all the remote URLs next to their corresponding short names.

# The End






