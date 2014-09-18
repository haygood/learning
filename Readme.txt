I'm changing this for no good reason.
Will Github know I did this?

make changes
git add Readme.txt    (this stages the changed file for commit. Repeat this command to stage several files to include in the commit)
git commit -m "Message describing what changed since the last commit"    (this tells Git to commit the staged files)
git push               (this sends the current commit to the repository on github.com)

Before you can send something to the remote repository, you have to make the remote repository on-line, and then tell Git you plan to use that repository for the current project:

git remote add origin https://github.com/haygood/learning    (this relates the local repository this file is in to the appropriate online repository