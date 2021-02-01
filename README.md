# Git and GitHub Course

#### 1. [Lecture 1: Git and GitHub Introduction](#h1)
#### 2. [Lecture 2:Install Git(Mac os)](#h2)
#### 3. [Lecture 3:Install Git(Windows)](#h3)
#### 4. [Lecture 4:Enable Git commands autocomplete and colors on mac](#h4)
#### 5. [Lecture 5:Branching and Merging](#h5)
#### 6. [Lecture 6:How to send e-mail from GitHub](#h6)
#### 7. [Lecture 7:Git Tags-What,Why,When and How](#h7)
#### 8. [Lecture 8:Git Merge vs Git Rebase](#h8)

###### Summary of this Course.

##### 1. Lecture 1:

* Git - VCS - Version control system(Open Sourse), Very useful When more than one users working on the same Repositery.

*VCS has two Types

    *CVCS(Centralized VCS)-Directly perform commit and update into the Repository.
    *DVCS(Distrbuted VCS)-Mostly Used VCS in Git.
    
*Git and GitHub is Not same.

##### 2. Lecture 2:

*Download Git in Mac OS

##### 3. Lecture 3:

*check that your system have already installed Git or not by using git --version command.

*If Git is not installed in your system then download Git from https://git-scm.com/.

*Add your project to git

*Commands

  - Git init to initialize git.
  - Git status to displays the state of the working directory and the staging area.
  - Git add command adds a change in the working directory to the staging area
  - Git commit -m “…..” to add a commits in a main Respositery.
  - Git remote add origin https://github.com/RaghavAutomation/R...​
  - Git push -u origin master push all the commits into the master branch
  - Git log
  - Git —help to see all the commands used in Git.

##### 4. Lecture 4:

*Enable Git commands autocomplete and colors on mac

##### 5. Lecture 5:

*Create branch

   -Git branch "branch name".
   
*heckout branch

   -Git checkout "branch name".
   
*Merge new branch in master branch

   -Git merge "branch name"
   
*Delete branch

   -Git branch -d “branch name”     (delete from local).
  
   -Git push origin —delete “branch name”   (delete from remote).

##### 6. Lecture 6:

*Github - Repository - Settings - integration & services - add email.

*Test and validate by making some change in the project.

##### 7. Lecture 7:

*Checkout the branch where you want to create the tag

   Git checkout "branch name"

*Create tag with some name

   Git tag "tag name"

*Git tag -a v1.0 -m "ver 1 of .."  (to create annotated tags) 

*Display or Show tags

   Git tag
   Git show v1.0
   Git tag -l “v1.*”

*Push tags to remote

   Git push origin v1.0
   Git push origin --tags

*Delete tags (if required only)

   to delete tags from local :
   Git tag -d v1.0

*To delete tags from remote :

   Git push origin -d v1.0
   Git push origin --delete v1.0
   Git push origin :v1.0

*To delete multiple tags at once:

   Git tag -d v1.0 v1.1 (local)
   Git push origin -d v1.0 v1.1 (remote)

##### 8. Lecture 8:

*Git merge

   - Is a non-destructive operation
   - Existing branches are not changed in any way
   - Creates a new merge commit in the feature branch

*Git rebase

   - Moves the entire feature branch to begin on the tip of the master branch
   - Re-writes the project history
   - We get much cleaner and linear project history
