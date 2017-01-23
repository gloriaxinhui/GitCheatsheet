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


## 2. Downloading repos into personal computers and modifying
  * Download repository on your git cmd:
  * C:\Users\gzhang>git config --global user.name "your username"
  * C:\Users\gzhang>git config --global user.email yourusername@gmail.com
  * C:\Users\gzhang>git clone https://github.com/yourusername/hello-world.git
  
  * Try this if it doesn't work:
   * git config --system http.sslverify false
   *get director: dir
  * get into hello world
   * cd hello-world
   * dir

  * create new file:
   * echo "Nother new file!!!">>newfile.txt
   * dir

 * git add newfile.txt

 * Add comment:
   * git commit -m "created a new file for text"

## 3. Category 3


## 4. Category 4


## 5. Category 5


## 6. Category 6


## 7. Category 7
