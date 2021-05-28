## The future is already here — it’s just not very evenly distributed. -- William Gibson  

# Hello GitWorld
This is the git playground. You can learn and try git tricks here. 

# Git basic
Some terms:
* Fork
* Branch
* Clone
* Remote
* Origin and upstream
* Pull and Push
* Pull request
* fetch
* status and diff

# Handle branches across the forks
* Fetch a branch from upstream to origin (your fork)
    * check status: `$ git remote -v`  
    * check which branch has updates: `$ git remote -v update`  
    * add upstream: `$ git remote add upstream link-to-where-you-forked`  
    * fetch branch update from upstream: `$ git fetch upstream`  
    * create the branch locally and start tracking: `$ git checkout branch-to-focus`  
    * push the new local branch to your repo (origin): `$ git push origin`  
    * (optional) remove tracking on upstream: `$ git remote rm upstream`  
## Handle branches on local machine (via terminal)
* Prune the branches already deleted: `$ git fetch -p`  
* Delete the local merged branch: `$ git branch -d name_of_branch`  
* List all the branches: `$ git branch -a`  
* Check if you have anything to push (not checking pull): `$ git status`  

## Delete a remote branch  
* `$ git push origin --delete feature/login`  


# Submmodule  
You can add another git repo into your project as a submodule. In that case, the folder will have a mark with @ hash. 
* To add : `$ git submodule add link-to-repo`  
* To sync: `$ git clone --recurse-submodules`  
* To pull after a clone without submod: `$ git submodule init`  and `$ git submodule update`

Reference: https://git-scm.com/book/en/v2/Git-Tools-Submodules


# Using git with SSH key  
https://docs.github.com/en/github/authenticating-to-github/about-ssh

# A good practice of git branching
https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy#:~:text=GitHub%20Flow%20Considerations&text=Any%20code%20in%20the%20main,push%20work%20to%20the%20remote.
