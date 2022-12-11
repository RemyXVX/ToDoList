<<<<<<< HEAD
# To Do List

#### By **Remy Flores**

#### **To Do List**

## Technologies Used
* VSCode
* GitBash
* C#
* MSTest
* WindowPowershell

## Description
_Updating on previous project and applying C# into it. Plus testing our lines of code through the Red/Green Method._

## Webpage
* https://github.com/RemyXVX/Pierre-s-Bakery-TTD

## Setup/Installation Requirements
* _Chrome web browser for best compatiblity_
* _Have a prompt and editor to apply changes, like VSCode and Gitbash_

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Download here for VScode](https://code.visualstudio.com/download)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Download here for Gitbash](https://git-scm.com/downloads)

* _Installation of .Net 6.0 and C# for applied language_

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Download here](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)

* _From there download repo for **Pierre's Bakery**_

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Copy here](weblink here)

## Step by step breakdown on how to run application: ##
<br>

<big>copy by running:</big>

```
git clone "[insert place here]"
````

<big>I would recommend also setting up work envirnoment after cloning by:</big>

```
dotnet build
```

<big>Afterwards:</big>

```
dotnet run
```

<big>This way we can double check for errors in our could that need to be addressed.<br>
We can then run our test:</big>

```
dotnet test
```

## Known Bugs
* _Testing is still being done. Will come back with an errors or bugs_

## License
* **SEE LICENSE [HERE](./LICENSE.txt)** 
=======
## What Is This?
 
This is an example repo corresponding to multiple lessons within the LearnHowToProgram.com walkthrough on creating a To Do List application in [Section 3: Database Basics](https://www.learnhowtoprogram.com/c-and-net/database-basics).
 
This project corresponds to the classwork and lessons that describe how to connect an ASP.NET Core MVC project to a MySQL database using [the MySqlConnector package](https://mysqlconnector.net/). Here are the lessons in the series:

- [Introduction to MySQL Workbench: Creating a Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/introduction-to-mysql-workbench-creating-a-database)
- [Connecting a Database to an ASP.NET Core App with MySqlConnector](https://www.learnhowtoprogram.com/c-and-net/database-basics/connecting-a-database-to-an-asp-net-core-app-with-mysqlconnector) 
- [Retrieving Objects From the Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/retrieving-objects-from-the-database)
- [Testing Database Backed Applications](https://www.learnhowtoprogram.com/c-and-net/database-basics/testing-database-backed-applications)
- [Creating a Test Database: Exporting and Importing Databases with MySQL Workbench](https://www.learnhowtoprogram.com/c-and-net/database-basics/creating-a-test-database-exporting-and-importing-databases-with-mysql-workbench)
- [Using the Test Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/using-the-test-database)
- [Deleting Objects in the Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/deleting-objects-in-the-database)
- [Testing for an Empty Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/testing-for-an-empty-database)
- [Overriding Equals and GetHashCode](https://www.learnhowtoprogram.com/c-and-net/database-basics/overriding-equals-and-gethashcode)
- [Saving Objects in the Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/saving-objects-in-the-database)
- [Finding Objects in the Database](https://www.learnhowtoprogram.com/c-and-net/database-basics/finding-objects-in-the-database)
 
## How To Run This Project

### Install Tools

Install the tools that are introduced in [this series of lessons on LearnHowToProgram.com](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c).

### Set up the Databases

Follow the instructions in the LearnHowToProgram.com lesson ["Introduction to MySQL Workbench: Creating a Database"](https://www.learnhowtoprogram.com/c-and-net/database-basics/introduction-to-mysql-workbench-creating-a-database) to create a `to_do_list_with_mysqlconnector` database with an `items` table.

Next, follow the instructions in the LearnHowToProgram.com lesson ["Creating a Test Database: Exporting and Importing Databases with MySQL Workbench"](https://www.learnhowtoprogram.com/c-and-net/database-basics/creating-a-test-database-exporting-and-importing-databases-with-mysql-workbench) to create a `to_do_list_with_mysqlconnector_test` database with an `items` table.

### Set Up and Run Project

1. Clone this repo.
2. Open the terminal and navigate to this project's production directory called "ToDoList".
3. Within the production directory "ToDoList", create a new file called `appsettings.json`.
4. Within `appsettings.json`, put in the following code, replacing the `uid` and `pwd` values with your own username and password for MySQL. For the LearnHowToProgram.com lessons, we always assume the `uid` is `root` and the `pwd` is `epicodus`.

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list_with_mysqlconnector;uid=root;pwd=epicodus;",
      "TestConnection": "Server=localhost;Port=3306;database=to_do_list_with_mysqlconnector_test;uid=root;pwd=epicodus;"
  }
}
```

5. Within the production directory "ToDoList", run `dotnet run --environment Development` to start the project in development mode, or `dotnet run` to start the project in production.
4. Open the browser to _https://localhost:5001_. If you cannot access localhost:5001 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/c-and-net/basic-web-applications/redirecting-to-https-and-issuing-a-security-certificate).
>>>>>>> 6356154b582983472b23da7e42220da8bdd3bb9d
