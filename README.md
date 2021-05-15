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


# Submmodule  
You can add another git repo into your project as a submodule. In that case, the folder will have a mark with @ hash. 
* To add : `$ git submodule add link-to-repo`  
* To sync: `$ git clone --recurse-submodules`  
* To pull after a clone without submod: `$ git submodule init`  and `$ git submodule update`

Reference: https://git-scm.com/book/en/v2/Git-Tools-Submodules

