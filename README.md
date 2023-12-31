# Github-3.1-Ramesh  `rgb(9, 105, 218)`

# Common Github Codes ##


<sub> 
  
## HOW TO SETUP github ##
  
+ git config --global user.name “[firstname lastname]”  &nbsp; &nbsp;- set a name that is identifiable for credit when review version history

+ git config --global user.email “[valid-email]”  &nbsp; &nbsp;- set an email address that will be associated with each history marker

+ git config --global color.ui auto &nbsp; &nbsp;- set automatic command line coloring for Git for easy reviewing

## BRANCH & MERGE ##

 * git branch  &nbsp; &nbsp; - list your branches. a * will appear next to the currently active branch 

*  git branch [branch-name]     &nbsp; &nbsp;-            create a new branch at the current commit

*  git checkout               &nbsp; &nbsp;-             switch to another branch and check it out into your working directory 

*  git merge [branch]          &nbsp; &nbsp;-             merge the specified branch’s history into the current one

*  git log                     &nbsp; &nbsp;-             show all commits in the current branch’s history

## SHARE & UPDATE ##

* git remote add [alias] [url]   &nbsp; &nbsp;-       add a git URL as an alias

* git fetch [alias]             &nbsp; &nbsp;-       fetch down all the branches from that Git remote

* git merge [alias]/[branch]    &nbsp; &nbsp;-       merge a remote branch into your current branch to bring it up to date

* git push [alias] [branch]     &nbsp; &nbsp;-       Transmit local branch commits to the remote repository branch

* git pull                      &nbsp; &nbsp;-       fetch and merge any commits from the tracking remote branch


## INSPECT & COMPARE ## 

+ git log                    &nbsp; &nbsp;-        show the commit history for the currently active branch
  
+ git log branchB..branchA    &nbsp; &nbsp; -   show the commits on branchA that are not on branchB

+ git log --follow [file]     &nbsp; &nbsp;- show the commits that changed file, even across renames
  
+ git diff branchB...branchA    &nbsp; &nbsp;- show the diff of what is in branchA that is not in branchB
  
+ git show [SHA]             &nbsp; &nbsp; - show any object in Git in human-readable format


</sub>
