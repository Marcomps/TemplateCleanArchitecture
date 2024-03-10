Template Clean Architecture
* Code first
* Unit of Work
* IoC

Command for create the DB using Package Manager Console

step 1
Add-Migration InitialCreate -p NorthWind.EFcore.Repositories -s NorthWind.EFcore.Repositories -c NorthWindContext

step 2
Update-Database -p NorthWind.EFcore.Repositories -s NorthWind.EFcore.Repositories -context NorthWindContext
