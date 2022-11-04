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