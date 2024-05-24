# Creating an Azure SQL Database
---

# Table of Content
1. [Creating Azure Server Instance](#creating-azure-server-instance)
2. [Create Database](#create-database)
3. [Connect to the Server Locally](#connect-to-server-locally)
4. [Query the Database](#query-the-database)

## Creating Azure Server Instance
1. Login to the [Azure Portal](https://portal.azure.com/).
2. Click on  __+ Create a Resource__.

3. Select the __Database__ blade and click on __SQL Server__.

4. On the __Basics__ tab, Select an Azure subscription and Resource Group in the project details section. 

5. In the Instance details section input a server name and select region.

6. In the Authentication section, select an authentication type. 
>> The authentication type selected is __SQL Authentication__ and it requires a username and password to be inputted.

7. Leaving every other tabs as default click on __Review + Create__.

8. Once validation is complete click on __Create__.

## Create Database
1. Once the server instance has been deployed, go to the resource.

2. In the __Overview__ tab click on __create database__.

3. In the database details section input a databse name.

4. In the __Networking__ tab add current IP address.

5. Leaving everyother tab as default, select __Review + Create__ once validation is done click __Create__.

## Connect to Server Locally
To connect with the server locally a VsCode extention, __SQL Server (mssql)__ was used.

1. Click on the extention icon on VsCode.

2. Click on __Add Connection__ and follow the prompt to input the serever name, database name, select an authentication type, input username and password.

3. Once Connection is made, you would see the database on the side-pane.

## Query the Database
In this section queries to create, update, filter and delete data would be done.

1. Right click on the database and select add new query.

2. In the code editor that opened insert queries:

- __Create Table and Populate Table__

- __Retrieve all data in the table__

- __Select a particular data from the table__

- __Update details__

- __Delete Details__

>> Once a query is inputted, ensure to run the query to ensure it executes.
