
# ***Planning***
- VCS
- GIT
- Git branch
- Fork
- Diferrence between fork and branch
- Advantages and disadvantages of using Git

When you take a look at the defenition in google of git you will see that Git is a version Control system (VCS)
    **What is version Control system?**
    
# ***A version Control system:***
* A system that tracks changes to a file or set of files over time
* Sharing on multiple computers
* Logging where be changed
* If you screw things up or lose files, you can easily recover 

# ***Types of VCS***

There are 3 types of VCS:
1. Local Version Control System 
2. Centralized Version Control System
3. Distributed Version Control System

## **_Local Version Control System_**
For example "Skype" 
![image](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/local-version-control.png)

A local version control systtem has advantages(+) and disadvantages(-):
   + This approach is very common and simple (+)
   - The chances of accidentally writing to the wrong file is higher(-)

That's why this methode is changed and another `VCS` is appered which is *`Centralized Version Control System`*

## **_Centralized Version Control System_**
![image](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/Centralized-Version-Control-System.png)

The best example of *`Centralized Version Control System`* is [*_SVN_*](https://fr.wikipedia.org/wiki/Apache_Subversion)

Also this type of VCS has advantages(+) and disadvantages(-):

   +Relatively easy to set up

   +Enable admins control the workflow

   On the other hand

   -If the main server goes down developers can’t save versioned changes

   -Remote commits are slow
   
   -If the central database is corrupted the entire history could be lost (security issues)

That's why this methode is changed and another `VCS` is appered which is *`Distributed Version Control System`*

### **Distributed Version Control System**
![image](https://cdn.shortpixel.ai/spai/w_738+q_glossy+ret_img+to_webp/https://serengetitech.com/wp-content/uploads/2020/12/distributed-version-control.png)

For exemple : Git

![image](/image/gitgithub%20-%20Copie.png)

## _Version control software_
Ther are 3 best version control software:
![image](/image/VCS.png)

As you can see in this table we can see the devolpere of different of verrsion control software

|***2015***                   |***2018***                   |
|:---------------------------:|:---------------------------:|
|Git: 69.3%                   |Git: 88.4%                   |
|Subervsion: 36.9%            |Subervsion: 16.6%            |
|Team Foundation: 12.2%       |Team Foundation: 11.3%       |
|Mercurial: 7.9%              |Mercurial: 3.7%              |

These are the last updates in Git (2022)


![image](/image/Gitpng.png)

* Open-Source System: it is a system for which the source code is freely and easily available. This source code is the original one which can be further modified.
* Distributed System: it is present on the server.Also, it can be taken from the developer’s computer. This means that the repository is present in a distributed network apart from the central server.
* Control System
* Version Controlled: Whenever more and more code is added to the folder, the code present in the Git folder gets changed.

We can also use an online hosts such as *`GitHub`* or *`Bitbucket`* to store a copy of the files and their revision history and that can merge the changes

In this picture we can see the relationship between the developer, the coworker and the web service 

![image](/image/Image0.png)

### *The main states:*
Git has 3 main states that your file can reside in which are:
* Modified
* Staged
* Committed

Git has 4 main code which are represented in this cercal

![image](/image/image3.png)

The basic steps on Git to push the project into an online host

    $ git init                    (1)
    $ git add .                   (2)
    $ git commit                  (3)
    $ git remote add <name> <url> (4)
    $ git push -u <name>          (5)(6)
    $ git pull                    (6)(5)

Let'ss strat with:
### **Git add**
    - git add <path>
    - git add .
    - git add -A

It selects file(s) and moves it to the straging area

The next step is:
### **Git push**
It is used to upload content from a local repository to a remote repository 

### **Git commit**
![image](/image/image2.png)

# ***Git branch***
This is a sloution to work in group in Git

![image](/image/image9.png)
### **Commands related to branch**
These are the commands that are related to ``branch``

    $ git branch 
    $ git checkout
    $ git clone
    $ git merge <branch name>

### **Git checkout**
This command make us switch the branch

![image](/image/Image22.png)

### **Git clone**
It is used to target an existing repository and create a copy of the target repository

1. git clone allows to create a copy of a target repository

2. The target repository can be local or remote.

3. Git supports a few network protocols to connect to remote repositories

4. Several different configuration options are available to change the contents of the clone.

### **Git merge**
1. The Git merge combines multiple sequences of commits into a unified commit history.
2. There are two main types of Git merges: fast-forward and three-pronged.
3. Git can automatically merge commits unless there are conflicting changes in the two commit sequences

There is another solution to work in groupe in git which is _`Fork`_

* You can make changes to a project without affecting the original repository
* Also, you can submit changes to the original repository with pull requests.

**So what is the differenc between Fork and branch well?**

Just imagin that you work in groupe in a small society and you trust the other people because you know them. So, you can use the `branch` as a solution of working in groupes. You can have a close communiaction between each other. Also, you give the development organization to write an access to a repository. And of cousre we don't forget the rapid iteration cycle between developpers. 

Otherwise, if you work in a society but you don't trust anyone. So, you can't use the `Branch` because may be one day some one can delete an important file. So, in this case, you should use `Fork`.So, you can fine-grain control over merging.Also, You expressly want to support independent branches. And of course, You want to discard experiments and changes easily.
