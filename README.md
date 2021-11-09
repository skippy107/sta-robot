# sta-robot #

This is an empty Robot Framework project that includes a Jenkinsfile suitable for use with a pre-built Docker image containing Robot Framework.



### Installation and Use ###

* Create a new empty repository on Github, note default branch name and repo URL
* Add the Jenkinsfile and .gitignore files to an empty folder
* Initialize the folder with Git - git init
* Stage all files for commit with Git - git add *
* Commit the changes - git commit -m "initial commit"
* Set the main repo branch - git branch -M ``default branch name``
* Set the repo remote to the repo URL - git remote add origin ``repo URL``
* Push the initial commit - git push -u origin ``default branch name``
* From Jenkins add a new pipeline
* Navigate to the new repo
* Jenkins will pull the tests and the Jenkinsfile then automatically build the pipeline and run it


