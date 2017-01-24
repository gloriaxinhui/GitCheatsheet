 # Git Cheat Sheet

## 1. Glossary of Terms
  * branch: an active line of development
  * commit:
    * (noun) a single point in the Git history; the entire history of a project is represented as a set of interrelated commits
    * (verb) the action of storing a new snapshot of the project’s state in Git history
  * fetch: to get the branch’s head from a remote repository, to find out which objects are missing from the local object database, and        to get them too
  * head: a named reference to the commit at the tip of a branch (aka head ref)
  * merge: to bring the changes from one branch into another branch
  * pull request: proposed changes to a repository submitted by a user and either accepted or rejected by a repostory’s collaborators
  * pull: pulling a branch means to fetch it and merge it. for example, if someone edits a remote file you’re both working on, you’ll          want to pull in the changes to your local copy
  * push: to send committed changes to a remote repository
  * repository: a collection of project files, documentation, and revision history


## 2. Downloading a working copy, making changes, and pushing those changes back to the github repository
  * Download repository using Git CMD (a command line shell that is installed with Git for Windows):
    * C:\Users\gzhang>git config --global user.name "your username"
    * C:\Users\gzhang>git config --global user.email yourusername@gmail.com
    * C:\Users\gzhang>git clone https://github.com/yourusername/hello-world.git
  
  * Try this if it doesn't work:
    * git config --system http.sslverify false
    * view directory: dir
    
  * Change directory into hello-world
    * cd hello-world
    * dir

  * Create new file:
    * echo "Nother new file!!!" >> newfile.txt
    * dir

  * Add the new file into the working copy
    * git add newfile.txt

  * Commit any changes you've made, and comment on those changes
    * git commit -a -m "created a new file for text"

  * Push changes back to the github repository
    * git push

## 3. Setting Up Git for Windows
  * git config --system http.sslcainfo "C:\Users\CPeterson\AppData\Local\Programs\Git\mingw64\ssl\certs\ca-bundle.crt"
    * This command fixes an initial error where Git does not know where this certificate is installed.


## 4. Basic windows commands on comandline
  * get information from a directory:
   * dir
  * get into an existing directory/ folder:
   * cd itc134
  * get out from an existing directory/ folder:
   * cd ..


## 5. Branch Diagram
  * Craig will take a stab at creating a simple Branch, Pull Request, Merge diagram.


## 6. Category 6


## 7. Basic Linux commands on comandline
  * list commonds:
   * ls
