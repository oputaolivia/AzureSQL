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
![0](https://github.com/oputaolivia/AzureSQL/assets/72948572/dbf454ba-438c-42ee-b379-fb0344381cd9)

3. Select the __Database__ blade and click on __SQL Server__.
![1](https://github.com/oputaolivia/AzureSQL/assets/72948572/97d8deb0-0140-4bf3-9659-0993dd75169b)

4. On the __Basics__ tab, Select an Azure subscription and Resource Group in the project details section. 

5. In the Instance details section input a server name and select region.
![3](https://github.com/oputaolivia/AzureSQL/assets/72948572/fe37327e-baa2-42fd-b125-1f80632c94f0)

6. In the Authentication section, select an authentication type. 
>> The authentication type selected is __SQL Authentication__ and it requires a username and password to be inputted.
![4](https://github.com/oputaolivia/AzureSQL/assets/72948572/7d5a3944-2602-4f88-8b1b-2287869d853e)

7. Leaving every other tabs as default click on __Review + Create__.
![6](https://github.com/oputaolivia/AzureSQL/assets/72948572/6061848c-8f85-4fd6-b7d1-6537ca920f3b)

8. Once validation is complete click on __Create__.

## Create Database
1. Once the server instance has been deployed, go to the resource.
![7](https://github.com/oputaolivia/AzureSQL/assets/72948572/4ea0cf1e-1905-4d9c-8fbf-d41777227c50)

2. In the __Overview__ tab click on __create database__.
![8](https://github.com/oputaolivia/AzureSQL/assets/72948572/2246e098-566b-4547-ab75-2e451d603ea8)

3. In the database details section input a databse name.
![9](https://github.com/oputaolivia/AzureSQL/assets/72948572/3e8293b2-9269-47d0-9868-23bcac8dbb2a)

4. In the __Networking__ tab add current IP address.
![10](https://github.com/oputaolivia/AzureSQL/assets/72948572/d847911b-22dd-4430-8817-2c2ddd5e5570)

5. Leaving everyother tab as default, select __Review + Create__ once validation is done click __Create__.
![11](https://github.com/oputaolivia/AzureSQL/assets/72948572/9acc1c78-9648-403b-be47-d5bab91847e9)

## Connect to Server Locally
To connect with the server locally a VsCode extention, __SQL Server (mssql)__ was used.
![server](https://github.com/oputaolivia/AzureSQL/assets/72948572/b5d3566c-0ff2-4d7b-9860-c3290a74e44b)

1. Click on the extention icon on VsCode.

2. Click on __Add Connection__ and follow the prompt to input the serever name, database name, select an authentication type, input username and password.
![13](https://github.com/oputaolivia/AzureSQL/assets/72948572/15118f27-f0f0-4a60-a3b0-0a7686415167)
![14](https://github.com/oputaolivia/AzureSQL/assets/72948572/0fe93ee6-c8b2-4069-891d-c6ce48e92dda)
![15](https://github.com/oputaolivia/AzureSQL/assets/72948572/65c8a9a4-ab80-499e-af78-415ac050b270)
![16](https://github.com/oputaolivia/AzureSQL/assets/72948572/cabf6035-74d9-4f43-8bd0-2ebd79c59632)
![17](https://github.com/oputaolivia/AzureSQL/assets/72948572/c1b33e37-4b18-42bd-b368-2a051966143b)

3. Once Connection is made, you would see the database on the side-pane.

## Query the Database
In this section queries to create, update, filter and delete data would be done.

1. Right click on the database and select add new query.

2. In the code editor that opened insert queries:

- __Create Table and Populate Table__
![20](https://github.com/oputaolivia/AzureSQL/assets/72948572/4101d15b-58ce-4a92-b6d7-99b51eeb39a8)
![21](https://github.com/oputaolivia/AzureSQL/assets/72948572/42f3fa4d-d4f4-4269-9fbf-6321e0e02771)

- __Retrieve all data in the table__
![22](https://github.com/oputaolivia/AzureSQL/assets/72948572/95778133-e1ac-413d-bd4a-f53d61061d97)

- __Select a particular data from the table__
![23](https://github.com/oputaolivia/AzureSQL/assets/72948572/c134f72d-7c43-44a6-bff2-1ece03a68ba2)

- __Update details__
![24](https://github.com/oputaolivia/AzureSQL/assets/72948572/540e0a4c-2296-40d0-a02a-fae7ebe7d329)

- __Delete Details__
![25](https://github.com/oputaolivia/AzureSQL/assets/72948572/ec220243-67b0-4fd1-9f5b-647212a17788)

>> Once a query is inputted, ensure to run the query to ensure it executes.
