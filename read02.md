# Git Tutorial: A Comprehensive Guide



![gitfigure](https://res.cloudinary.com/practicaldev/image/fetch/s--ShHSfi-a--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/1N2U2i2Z2C16/Image%25202018-04-11%2520at%252012.47.23%2520PM.png)


## version control
is a system that allow us to control different files from the same place , and it allow us to revisit various versions of a file or set of files by recording changes

there is many types of version control, these are two of them:

 * Local Version Control : this is a tool developed by programmers to entains one database on your hard disk and stores changes to files.
 * Centralized Version Control : This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases),and this allows programmers to have more knowledge and expereince.

## what is get ?

***Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.***

## history of get 
Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company.Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git.git could support large projects, have stong preventing corruption techniques, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## Download Git

git can be downloaded in 3 ways which are 
 * Install as a package
 * Install via another installer
 * Download and compile the source code.

## Graphical Clients
Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.


## Setting up a Git Repository
* `cloning`: but copying and paste the link of the code botton in github of your repository into your command line after "git clone"
* `importing `: its by using 3 command lines in command line which are :

## what is git and github ?

firstly, we will talk about the difference between git and git hub :

 * github: github is a famous platform that you can share you project on so that other developers can see your work and edit it, and its a very usefull tool to have back up of your projects in case your PC is destroyed.
 

* git: its a very usefull way that can clone our projects from our github account to our local computer,sothat we can edit it from our computer without going back to the github account. its a very usefull tool between developers so that they can exchange their work and work with each other.

![gitfigure](https://res.cloudinary.com/practicaldev/image/fetch/s--ShHSfi-a--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/1N2U2i2Z2C16/Image%25202018-04-11%2520at%252012.47.23%2520PM.png)

## history of get

***Git  is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems)***

## Setting up a Git Repository
* cloning : but copying and paste the link of the code botton in github of your repository into your command line after "git clone"
* importing : its by using 3 command lines in command line which are :

"git add ." , "git commit -m "what ever you want" , "git push origin main "

## Local Repository Structure
### The local Git repository has three components:

***Working Directory(The actual files reside here) , Index(The area used for staging) , Head(Points to the most recent commit)***

![figure](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

<<<<<<< HEAD
## The Life Cycle of File Status
the life cycle of file is on three stages: 

![img](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)


* After you edit a file, Git flags it as modified because of changes made after the previous commit.
* You stage the modified file.
* Then, you commit staged changes.

## Committing a File
 after changing what you want in the file , you can commit it by :

 `$ git commit -m “made change x,y,z”`

 ## Committing All Changes

 by using `$ git commit -a`
 
## Pushing Changes

you can push your changes from your local computer to github by :

`$ git push origin master`

# cloned repositories



## Seeing Your Remotes
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.
## contact me 

this [link](https://github.com/ahmadalrasheed) is my github link ! thank you very much !

this [link](https://github.com/ahmadalrasheed) is my github link ! thank you !



