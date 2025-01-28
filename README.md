# azureSQL_register
Template for registering a user to a database in azure through spring boot app

1.  Edit the application.properties file in src/main/resources 
and update the datasource.url line with your SQL server and SQL database (inside your server) that is on Azure.

2.  Set username and password to an account with write access (such as db_owner) that exists in that database (reagular SQL account, not entra / microsoft account).
   You must create this user manually if you did not do so while creating the database at creation time.

3.  Make sure you have a table named "Users" inside your database.

yadayada more later
