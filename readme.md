This project is a example how we can make a etl process with SSIS.

Objective:
This project project process a file with name "test.xlsx" which contains information about user. This inoformation must be update the table USERS_TEST.

Steps:
1. run querry in "queries.sql" to create database "SSIS_TEST"
2. run queriy in "queries.sql" to create table "USERS_TEST" in database "SSIS_TEST"
3. deplloy ssis project, you can do this with this guide:
    https://learn.microsoft.com/en-us/sql/integration-services/packages/deploy-integration-services-ssis-projects-and-packages?view=sql-server-ver16
