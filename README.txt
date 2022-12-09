28th Oct, 2022
Name: Jay Patel 
Project Name: JayBookStore

1059 
Set up the project
Named it JayBookStore 
select ASP.NET core WebApp (Model View-Controller)
Select an individual account authentication 
Create a WebApp using ASP.NETcore 3.1 in the Visual Studio 2019
Comment ssl port 

1316
set up bootstrap 
first go the Bootswatch.com 
select a VAPOR theme
then download its bootstrap.css file 
after that replace the existing bootstrap.css 
then change the site.css file 
go to the views folder in the change the existing bootstrap.min.css to bootstarp.css

1320 
change the nav class 
remove the text-dark 
lastly remove references to "text-dark"
then test the app 

31st oct, 2022
completed bootstrap

4th November, 2022
1014
add three project and named it 
JayBooks.DataAccess
JayBooks.Models
JayBooks.Utility

1020
Copied data folder and 
paste to the .DataAccess project
and delete the original one..

1025
Installed NuGet Packages 
.EntityFrameworkCore.Relational 
&
.SqlServer packages
after that delete the migrations folder 

1029
Install Another NuGet package 
.EnityframeworkCore
All the above version installed using version (3.0.16)

1031
Delete default Class1.cs file from all the projects
then build the project 

1037
Move models in JayBooks.Models and 
delete the original 
After that Modified the Error.cshtml file 
Addded project reference 

1040
renamed the Models folder to the ViewModels 
replaced the ErrorViewModels.cs to the .Models.ViewModels 
Rebuild the project 

1045 
modify the Startup.cs 
and Comment down the data statement 
Run the application and  application shows 4 errors 
corrected the default reference ErrorViewModel to the new .Models.ViewModels.ErrorViewModels 
rebuild and cleaned the project but the errors still occured  

1145
step 4 still pending 
total 11 commits
update and commit to the git 
stop working.......

1236 
open repo in lab PC
start working but errors still there
.....
stop working... 

2022-11-11
due to word mistake i got two errors in the error.cshtml and errorViewModel.cs file 
run application 
its run...:)

2022-11-12
start working on the project
In the Utility project, createda static details class called SD.cs
Modify the properties of the class
Add project reference to the main project
In the DataAccess project add project references t o Models and Utility

2348

Added a ‘Customers’ area to Areas
Changed the routes in Startup.cs like the one outlined in the ScaffoldingReadMe.txt
Moved the HomeController.cs to the Area > Customer > Controller folder and delete Data and Models.
Edit the HomeController.cs to explicitly define that the controller is in the Customer Area
Moved Views > Home and modify the HomeController namespace
Rebuild and clean the project 
right there is zero errors 
then run the application 
it runs .........
Copy _ViewImport and _ViewStart to Customer Area
Modify the _ViewStart.cshtml to reflect the new path
Run the application now
it runs perfect..

2352
Added a new Admin area in Areas
Added the proper view files and delete the Data and Models folder
Delete the Controllers folder
Update the GitHub repo......
Finished Part 1 with zero errors....

2022-11-14

1250
Created the migrations (using code-first, where changes are “pushed” to the database), modify the database name and save.
Use the NuGet Package Manager Console to add the migration (with a meaningful name).
Note what happens if the wrong default project is selected.
Change to the correct default project (.DataAccess) and run again.
Added the new migration file name entry in the README.
Added a new table to the DB by creating a Category model and push it to the DB:
Added a new class file to the .Models project and modify
Added the migration via the PM Console
migration file name: 20221114045924_AddDefaultIdentityMigration.cs
The new migration file will be empty because it hasn’t been added to the Application DB Context
Update this and note the added using statement
Re-run the add-migration and review the changes to the AddCategoryToDb (resolve the duplication error that will occur).
Update the database, confirm the new Categories table via the SQL SOE and push commits to GitHub
rebuild 
and
clean the project 



1257
Add a new folder name it ‘Repository’ (for class implementations of interfaces) and add an IRepository (for the interfaces) folder inside it.
Add a new item of type interface to the folder and name it IRepository.cs 
Modify the code to create the constructors and dependency injection (DI)
from Assignment 2 folder
rebuild 
and
clean the project 

2022-11-14

Started working on the project 
rebuild and clean 
Create individual repos for category  
CategoryRepository.cs
ICategoryRepository.cs
Modified CategoryRepository 

1314
Modified ICategoryRepository interface
Review and modify the error now in CategoryRepository.cs (implement the interface to update)
Complete the remaining modifications (note the comments)
Rebuild, fixed any error showing and 
push commits to GitHub
getting constant error so started on the new project 


2022-11-18
Create the project.
JayBookStore is its name.
decide on an ASP.NET core WebApp (Model View-Controller)
choosing a unique account authentication
Create a WebApp in Visual Studio 2019 using ASP.NETcore 3.1.
Ssl comment port
build a bootstrap
visit Bootswatch.com first
choosing a VAPOR theme
the bootstrap.css file for it, then
then swap out the current bootstrap.css
then make the site.css file changes.
update the existing bootstrap.min.css to bootstarp.css by going to the views folder.
alter the navigation class
Delete the dark text.
Remove all references to "text-dark" last.
then examine the app.
finished bootstrap
add three projects and give it a name
JayBooks.DataAccess
JayBooks.Models
JayBooks.Utility
copy of the data folder
the.DataAccess project by pasting
and discard the original.
NuGet packages were installed.
.EntityFrameworkCore.Relational
&
SQL Server packages in
then get rid of the migrations folder.
Setup an additional NuGet package
.EnityframeworkCore
Version installs all of the aforementioned versions (3.0.161031
Get rid of the default Class1.cs file from each project.
then construct the project.
Move the models in JayBooks.
Get rid of the original
modified the Error.cshtml file after that
Project reference added
changed the name of the Models folder to ViewModels.
ErrorViewModels.cs was swapped out for.Models.ViewModels.
Rebuild the project
but now i am getting 6 errors don't know how :(..
so worked on the first one again 
completed till the part 3 
forgot to coomit 


2022-12-9
final commit 
and subit the link