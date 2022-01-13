# SIGGD-Unity-Template
Template for creating new Unity GitHub repositories.
How to setup:
  1) Click the "Use this template" button to make your own duplicate repository on GitHub
  2) Download and setup the new reposotory to your computer (Using GitHub Desktop is reccomended)
  3) Create a new Unity project in the repository folder
  4) Move the Unity project files so that they are not in a subfolder of the repository folder (the gitignore will not work otherwise)
  5) Commit the changes to the Master branch
  6) The repository should now be ready for use

General use:
  1) Have members of your team each create branches for all new changes after this to avoid overwriting anyone's work
  2) Once something on a branch is "done" pull the latest branches from master into your own branch
  3) Check that your branch still works with the newest master changes
  4) Create a pull request from your branch into master
  5) These pull requests will be checked by one of the project leads and merged if able, if not, marge master into your own branch again and fix any conflicts

Additional notes:
  1) The GitIgnore is correct as of 9/11/2021 and will work for the 2021.x.xx versions of Unity. It is unlikely that it will change much, but if files are not being ignored properly, replace the code in the GitIgnore with the code here: https://github.com/github/gitignore/blob/master/Unity.gitignore
