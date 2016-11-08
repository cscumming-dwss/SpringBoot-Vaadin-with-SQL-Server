# Based on Vaadin Azure Webinar example

This is a simple full stack MS SQLServer2012 example, which connects to a SQL Server database running in locally with Windows Authentication, with the example data set (used ddl-auto:create) The Spring Boot application connects to that database using Spring Data's repository helpers and a Vaadin UI lets end users view and modify the data.

If you want to try out this application:

 * Install SQL Server or connect to an existing one you have access to, load the "Sample" data set which is used by this example
 * Change the connection string parameters (your server, user and password are different)
 * (Optional, for local running/development) make sure TCP/IP connections are setup and enabled so you can connect
 
