# ModernStackProject
 Top Project on Modern Stack (Snowflake, dbt, Looker)

# Overview 
The goal of the project to master dbt, Snowflake, VSCode, Looker  

## Step 1 
Create a connection to Azure PostgreSQL via Flexible Server on DBeaver. 
Configure connection providing valid credentials.  

#### Download DBeaver 

Please use this link to download DBeaver - a free universe database tool:
[DBeaver Community Edition](https://dbeaver.io/download/)

Once downloaded, launch the tool on your machine

#### Create a connection to Azure PostgreSQL via Flexible Server

To create a connection, you need to follow these steps: 

> Click on the "New Database Connection" button in the toolbar at the top left-side

Alternatively, you can use this option:  

>  Click on the "Database" menu and select "New Database Connection

Then you need to: 

> Select PostgreSQL: In the "Connect to a database" dialog, choose "PostgreSQL"
> from the list of available databases and then click "Next."

Then you need to configure connection: 

```
Host: *****
Port: Leave the port number as default option 
Database: Enter the name of the database you want to connect to.
If you're not sure, use the default "postgres" database.
Username: *****
Password: *****
```

If you are using PgBouncer for connection pooling: 

> Enter the port number to 6432.

## Step 2 
Plugin Snowflake and dbt 
dbt create models in dbt 

## Step 3 
to be continued




