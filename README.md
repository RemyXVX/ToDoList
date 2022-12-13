# To Do List

#### By **Remy Flores**

#### **To Do List**

## Technologies Used
* VSCode
* GitBash
* C#
* HTML
* JSON
* MySQL
* MSTest
* WindowPowerShell

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
$dotnet build
```
<big>Once we have the program settled, I would add an '_appsetting.json_' file like:</big>
```
$touch appsetting.json

and then add to the file:

{
  "ConnectionStrings": 
  {
    "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list_with_mysqlconnector;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```

<big>Afterwards,</big>

```
$dotnet run
```

<big>This way we can double check for errors in our could that need to be addressed.<br>
We can then run our test:</big>

```
$dotnet test
```

## Known Bugs
* _Testing is still being done. Will come back with an errors or bugs_

## License
* **SEE LICENSE [HERE](./LICENSE.txt)** 