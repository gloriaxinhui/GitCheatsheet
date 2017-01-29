
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
  * working copy: a copy of a repository that lives on your local computer temoporarily


## 2. Downloading a working copy, making changes, and pushing those changes back to the github repository
  * Download repository using Git CMD (a command line shell that is installed with Git for Windows):
    * C:\Users\yourusername>git config --global user.name "your username"
    * C:\Users\yourusername>git config --global user.email yourusername@gmail.com
  * Clone repository 
    * C:\Users\yourusername>git clone https://github.com/yourusername/hello-world.git
  
  * Try this if it doesn't work:
    * git config --system http.sslverify false
    * view directory: dir
    
  * Change directory into hello-world
    * cd hello-world
    * dir

  * Create new file:
    * echo "Another new file!!!" >> newfile.txt
    * dir
    * this also allows you to add more to the file
  
  * Overwriting a file
    * echo "Overwriting new file!!!">newfile.txt

  * Add a new file to version control
    * git add newfile.txt

  * Commit any changes you've made, and comment on those changes
    * git commit -a -m "created a new text file"

  * Push changes back to the github repository
    * git push
    
  * Remove your working copy directory (move up one to the parent folder first)
    * rmdir hello-world /s /q
   
  * Initializing a directory as a Git repo
    * git init
    
  * Stashing away uncommited mods temporarily
    * git stash
    
  * Re-applying last stashed changes
    * git stash apply

## 3. Setting Up Git for Windows
  * git config --system http.sslcainfo "C:\Users\CPeterson\AppData\Local\Programs\Git\mingw64\ssl\certs\ca-bundle.crt"
    * This command fixes an initial error where Git does not know where this certificate is installed.


## 4. Basic commands on command line
  * Display list of commands:
    * help (Linux and Windows)
  * List directories/files:
    * ls (Linux) dir (Windows)
  * Change to an existing directory:
    * cd directoryname (Linux and Windows)
  * Move up one directory level:
    * cd .. (Linux and Windows)
  * Change back to last directory you were in:
    * cd - (Linux only)
  * Create new file
    * echo "file content" >> filename.txt (Linux and Windows)
  * Delete file
    * rm filename (Linux) del filename (Windows)
  * Delete directory
    * rmdir /s /q directoryname (Windows) rm -rf directoryname (Linux)
  * Show your git commit logs
    * git log


## 5. Branching on windows command line.
 * tells you what branch you are on:
   * git branch
 * creating a new branch:
   * git branch new_branch
 * creating a new branch and switching to it:
   * git branch -b "branch_name"
 * deleting a branch:
   * git branch -d new_branch
 * switch branch:
   * git checkout new_branch
 * merge branch:
   * git merge master
 * change branch
   * git checkout branch_name
 * Push branch up to git
   * git push origin new_branch 
 * Shows what branch you're in
   * git branch
 * Update branch
   * git checkout
  

## 6. Branch Diagram
 * This Diagram will be illustrated by Craig! 
 * It will be a graphic, no text will be displayed here. 
