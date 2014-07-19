## git cheat sheet


### create & clone
* create new directory: mkdir [directoryname]
* change working directory: cd [newdirectory]
* clone remote repo to local: git clone [URL]

### add & remove
* add changes to index: git add [filename]
* add all changes to index: git add .
* remove/delete: git rm [filename]

### commit & synchronize
* commit changes: git commit -m "short message"
* push changes to remote repo: git push origin master
* connect local repo to remote repo: git * remote add origin [filepath, occasional]
* update local repo with remote changes: git pull
  
* to check the 'origin' location: git remote -v
  
### how to create a new repo and clone to desktop
1. Create repo on Github online
2. Clone the online repo onto local working directory
  * git clone URL

### how to update changes from local repo to remote repo
1. git commit -a -m "add short description here"
2. Push from local directory to the remote repo
  * git push origin master
  
* 'git status' to see the level of changes


### how to create new file in an existing repo and push changes to remote repo

1. Create new file
  * Touch [filename.extension]
2. Add new file to repo
  * git add [filename.extension]
3. Commit changes
  * git commit -m "add short description here"
4. Connect local directory/repo to the remote repo
  *git remote add origin
5. Push local directory to the Github online
  * git push origin master


