This Kubernetes setup allows you to retrieve and play mp3/wave files loaded onto the
executus-server application.

Once all the yaml files have been applied with kubectl the hosts file will need to be modified
on the local machine to include 

127.0.0.1   executus-app.local
127.0.0.1   executus-server.local

Then with a browser you can navigate to executus-app.local:8081.