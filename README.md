To revert a file in your feature branch to its original state from the develop branch, you can use the following steps:

Fetch the latest changes from the develop branch:

 
git fetch origin develop
Reset the file to the state of the develop branch:

 
git checkout origin/develop -- path/to/your/file
Commit the changes:

 
git commit -m "Revert file to its original state from develop branch"
Push the changes to your feature branch:

 
git push origin your-feature-branch
Replace path/to/your/file with the actual path of the file you want to revert and your-feature-branch with the name of your feature branch.

If you need any more assistance, feel free to ask!