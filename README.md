Bug Tracker Plugin
=============================

This is a jenkins plugin that allow Jenkins to connect to the bug tracker app with valid credentials in order to setup the status of bugs depending on a specific commit message that should match any of the patterns that jenkins user could specify whitin jenkins configuration of the project.

Steps to follow
-
- Go to Manage Jenkins -> Manage Plugins -> Advanced -> Upload Plugin
- Upload the hpi file 
- Go to Manage Jenkins -> Configure System -> Hello World Build 
- Specify the Bug Tracker app URL alongside of your credentials
- Click test connection button to check if your entries are correct
- Go to your project job -> Configure -> Add build Step -> Say Hello World
- Write a pattern to intercept from the commit message that should contains {id} of bug
- Select the status to setup when the pattern is valid
- Write down as many patterns as needed

Jenkins Extension
-
Configure System Step:

![](http://i66.tinypic.com/25p5k5v.png)


Configure project:

![](http://i67.tinypic.com/nn8c2c.png)
