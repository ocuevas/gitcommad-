#GIT 

##BASIC COMMANDS 

* $ git init  
    * Initialize Local Git Repository. 
* $ git add <file>
    * Add File(s) to Index.
* $ git status 
    * Check Status of your porject tree.
* $ git commit 
    * Commit changes in index.
* $ git push 
    * Pull Latest From Remote Repository 
* $ git pull
    * Pull Latest From Remote Repository 
* $ git clone 
    * Clone Repository into a new directory
* $ git branch <name> 
    * create a branch
    
if you want to remove any file from the stafing area use this command 
 $ git rm -- cached <file>

<<<<<<< HEAD

=======
 * $ git branch <name>
 * $ git checkout <name> -- Switch to a different branch. 
>>>>>>> demo

…or push an existing repository from the command line
* git remote add origin <Repository URL>
* git branch -M master
* git push -u origin master

Git has three main main states that your files can reside in: modified, stage, and committed.