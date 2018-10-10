# Lab 9: Setting up the Database

Make sure your machine is set up with [MySQL](https://dev.mysql.com/downloads/mysql/) and [MySQL Workbench](https://dev.mysql.com/downloads/workbench/).

1. Open MySQL Workbench. Click on the “+” button to create a connection.

1. Add the connection name as `packt`, username `root` and the password (if any). Click on “Test Connection” to see if the connection is correct, then click on "Ok".

1. Click on "Ok" to create the connection.

1. Now click on the the connection, `packt`

1. Create the todo database by running the following query, and click on the execute icon:
  ```sql
  CREATE DATABASE todo;
  ```

6. Copy and paste the [database schema](./raw-sql.sql) in MySQLWorkbench's query tab and click on the _execute_ icon
