##Step 1
Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.

##Step 2
Open Terminal.

##Step 3
Initialize the local directory as a Git repository.

git init

##Step 4
Add the files in your new local repository. This stages them for the first commit.

git add .
Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
Commit the files that you've staged in your local repository.

##Step 5
git commit -m "First commit"
Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
Copy remote repository URL fieldAt the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.

##Step 6
In Terminal, add the URL for the remote repository where your local repository will be pushed.

git remote add origin remote repository URL
Sets the new remote

##Step 7
git remote -v
Verifies the new remote URL

##Step 8
Push the changes in your local repository to GitHub.

git push -u origin master
Pushes the changes in your local repository up to the remote repository you specified as the origin
