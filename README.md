# First you need to have an on premise(local) openshift installation.

## 1.- # oc create new-project <projectname>

## 2.- # oc create new-app <git url "https://github/user/repo">
 

 # The oc clicente will search an image by Dockerfile an use it to do one build, creates one pod and creates a service, but does not create a route.

Then you must to login into your local openshift console, select the <projectname> go to services , select the last created service and then click into "Create Route" link icon.
 
 
