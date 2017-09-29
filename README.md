# SpringBootMultiDatabase
Spring boot using different types of database connections: 

<b>h2</b>: 
Embedded database which also is set up to use Flyway.

<b>mysql</b>: 
Connects with user created in MySQL called 'dev' whom requires no password. Tested on MySQL version 5.7.19.

<b>sql server</b>: 
Uses SQL Server Authentication to connect to local SQL Server db. Tested on SQL Server 2017 RC2. Follow these <a href="https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/change-server-authentication-mode#SSMSProcedureinstructions">instructions</a> to set up SQL Server correctly.
