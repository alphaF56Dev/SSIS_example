This project is an example about how we can make a etl process with SSIS.

Objective:
This project project process a file with name "test.csv" which contains information about users. This information must be update the table USERS_TEST.

Steps:
1. run querry in "queries.sql" to create database "SSIS_TEST"
2. run queriy in "queries.sql" to create table "USERS_TEST" in database "SSIS_TEST"
3. deplloy ssis project, you can do this with this guide:
    https://learn.microsoft.com/en-us/sql/integration-services/packages/deploy-integration-services-ssis-projects-and-packages?view=sql-server-ver16

Parameters in project:
    * source_file: path where the file is
    * destiny_file: path where the file will be copied

Important: Actually the nambe file must be "test.csv" if you like to change this value, you can change it directly in project.