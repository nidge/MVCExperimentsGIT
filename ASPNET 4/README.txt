
This sample application and the PDF have been downloaded from the address below

https://www.asp.net/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application

Getting Started
To build and run this sample as-is, you must have Visual Studio 2013 or Visual Studio 2013 Express for Web installed. 

If you have Visual Studio 2015, change the connection string in the Web.config file so that the SQL Server instance name is MSSQLLocalDB instead of v11.0.

In most cases you can run the application by following these steps:

Download and extract the .zip file.
Open the solution file in Visual Studio.
Build the solution, which automatically installs the missing NuGet packages.
Open the Package Manager Console, and run the update-database command to create the database.
Run the application.

If you have any problems with those instructions, follow these longer instructions.

Download the .zip file.
In File Explorer, right-click the .zip file and click Properties, then in the Properties window click Unblock.
Unzip the file.
Double-click the .sln file to launch Visual Studio.
From the Tools menu, click Library Package Manager, then Package Manager Console.
In the Package Manager Console (PMC), click Restore.
Exit Visual Studio.
Restart Visual Studio, opening the solution file you closed in the previous step.
In the Package Manager Console (PMC), enter the Update-Database command. (If you get the following error:
"The term 'Update-Database' is not recognized as the name of a cmdlet, function, script file, or operable program", exit and restart Visual Studio.)
Each migration will run, then the seed method will run. You can now run the application.

The code illustrates the following topics:

Creating a data model using data annotations attributes, and fluent API for database mapping.
Performing basic CRUD operations.
Filtering, ordering, and grouping data.
Working with related data.
Implementing connection resiliency
Using command interception
Writing async code
Handling concurrency.
Implementing table-per-hierarchy inheritance.
Performing raw SQL queries.
Performing no-tracking queries.
Working with proxy classes.
Disabling automatic detection of changes.
Disabling validation when saving changes.


