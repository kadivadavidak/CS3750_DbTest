# CS3750_DbTest

* Install mysql-connector-net-6.11.7 (8.0.11 kept crashing on me) - https://dev.mysql.com/downloads/file/?id=478087
* Install mysql-for-visualstudio-1.2.8 (2.0.5 gave me issues) - https://dev.mysql.com/downloads/windows/visualstudio/1.2.html
* (Make sure all three of the following are on the same version as the .net connector above (6.10.7))
* Install MySql.Data.Entity Nuget package (MySql.Data.Entity.EF6)
* Install MySql.Data Nuget package
* Install Mysql.Web Nuget package
* Right click Model folder in project view.
* Click Data in left
* Click ADO.NET Entity Data Model
* Give it a name
* Click Add
* Click EF Designer from database
* Next
* New Connection
* Choose MySQL Database
* Type in DB info
* OK
* Choose Yes, include sensitive...
* Give it a name
* Next
* Check Tables
* Finish

* Right click Controllers folder
* Add
* Controller
* MVC 5 Controller with read/write actions
* Add
* Name it
* Add using {project name}.Models; to controller
* Right click in controller -> Add view
* Run app.
