######## AFTER UBSTALLED GIT THEN CONFIGURING GIT ###########
* git config --global username "myname"
* git config --global user.email "email.com"
* git config --list  ## history ## (~) = (root directory folder)

######## Inside vsc terminal #######
* git --version
* git clone (url of HTTPS)
* cd apnacollege
* ls 
* ls -a to see headen files
* git status ## if you change in vso ## up to date = modified
** untracked ## new files that git doesn't yet track
** modified ## changed
** unmodified ## unchanged
######## git add . # all files starged 
######## git commit # if you changed then it changed in local not remote
######## git push # pushing local to remote like github

##### init commands
* git init = used to create a new git repo
* cd .. one step back
* mkdir ## creating folder in local and in vso 
* cd local
* ls -a
* . .. .Git
########## creating two files
* git status
* git add .
* git commit -m "add"
* git status
* git remote add origin URL
* git remote -v ## it see details of remotes
* git branch ## to check branch
* git push -u origin main ## fully code pushing to remote

###### Branch commands
* git branch 
* git branch -M main
* git chechout master ## we are in master
* git checkout -b ## to create new branch
* git branch -d master ## to deleting master branch
* git branch
* git checkout -b feature ## created the feature branch
* git checkout master ### we are in master branch

###### merging code
* git diff (branchname) ## to check different between code of branches
* git merge (branchname) ## to merge 2 branchs ##### way 2 to create PR
* git diff main ## to check the different betweent two branches code
* git merge main

#### pull command # two branches
** for example
* [ branch is abc ] and one guy changed code is 12345
* [ branch is xyz ] two guy changed code is 54321
** we want same code in both branches that's why using [ git pull origin xyz ] same code comes into both branches

#### Pull request
* one project working on multiple members so to push multiple member to same code github not accepted 
* so that's why pull request 
* first push updated code in pull request there out manager or senior will check code and merge to branch 
 
#### Resolving merge conflicts
* when two branches are pushing code to branch then git asks asks us which branch code can i push
* add accept current ## one branch
* accept incoming change ## two branch
* accept both branches code ## addes both branches code

### undoing changes like ( mistakes )
** case1: staged changes
* git reset (filename)
* git reset

** committed changes (for one commit )
* git reset HEAD~1    ### it will pull back last commit #

** commited changes ( for many commits )
* git reset ( commit hash ) ## all commits

** commited changes ( for many commit )
* git reset ( commit hash )
* git reset --hard ( commit hash )
* git reset ( file name )

### fork 
* fork is a rough copy