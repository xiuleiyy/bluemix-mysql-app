bluemix-mysql-app
=================

This an application running on Bluemix with Mysql service


==============================
How to run this app on Bluemix?
================================

1. Download this applciation to local workspace(Eclipse)
2. Export applicaiton to bluemix-mysql-app.war
3. Make connection with Bluemix by Command Line Tool
4. Use "cf push <app_name> -p bluemix-mysql-app.war" to deploy application to Bluemix.
5. From Bluemix UI: http://ace.ng.bluemix.net
6. Create a Mysql service on Bluemix UI and bind it to bluemix-mysql-app application.
7. Restart this applicaiton.
8. Access your application from http://<app_name>.mybluemix.net/
