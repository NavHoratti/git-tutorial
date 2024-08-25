When your command line is pointing to the correct directory

# [git init] - to set up git inside our designated folder.

# [git status] - this tells what changes has been made since our previous version

# [git add] - to add the changes in our next version

ex: git add file/folder name -> git add config.js [to add only a file or a folder]
ex: git add . [to add all the changes]

Once you add, do [git status] and check again if the files are staged properly.

# [git commit -m "Message"] - to commit your changes

# [git log] - to check the version history

If you missed adding one more file, just do the same proces with just a small change in git commit statement

git add .
git commit -m "Version" --amend

# Note

# When you do [git add .] or [git add filename] , it moves the files into the staging area.

# [git reset .] or [git reset filename], it takes out of the staging area.

So similarly if you want take the files out of the staging area, then we use [reset]

Also, if we want to [undo/ discard] the changes to the files in the working area, we use,

# [git checkout -- change.js] or [git checkout -- .] 


