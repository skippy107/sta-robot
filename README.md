# sta-sf #

This is an empty Robot Framework project that is intended for use with CumulusCI. The included Jenkinsfile is suitable for use with a pre-built Docker image containing CumulusCI.



### Installation and Use ###

* Create a new repository on Github
* Add the Jenkinsfile and .gitignore files to an empty folder
* Initialize the project with Git - git init
* Initialize the project with CumulusCI - cci project init
* Push all changes to the new repo
* From Jenkins add a new pipeline
* Navigate to the new repo
* Jenkins will pull the tests and the Jenkinsfile then automatically build the pipeline and run it


