# Assignment2 Using Microsoft SSIS Packages
This assignment is about manually exporting the HumanResources.Employee table from the AdventureWorks2014 OLTP database into a flat file and importing the flat file back into the same database using Microsoft Integration Services in Visual Studio.

Zip File contents:
1. Q1_Package.dtsx\n
      Using an SSIS package to manually export a table from a SQL server database to a flat file.
      The package has two Data Flows for the database table source connection and the flat file destination connection.
2. Q2_StagingTableCreation.sql:
      This SQL script creates an empty table in the destination SQL database as the staging table for the import.
3. Q3_Package.dtsx:
      The Control Flow in this package loads data from the flat file to the database table.
4. Q4_SSIS_Screen_Shots:
      This Word document drecribes the steps I took to export and import the data. It has screen shots of the Control FLows.
