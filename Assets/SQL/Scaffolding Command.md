
# Scaffolding Command

This the commmand to generate Model classes and DBContext classes using EF Core.
## How to create a model based on your existing database :

Scaffold-DbContext "Data Source=VINAY\SQLEXPRESS;Initial Catalog=CustomerDB;Integrated Security=True;Trusted_Connection=True" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models


### Parameter Description :
#### "Data Source=VINAY\SQLEXPRESS"
It refers to local SQLEXPRESS database server.
#### "Initial Catalog=CustomerDB"
Specifies the database name "CustomerDB" for which we are going to create classes.
#### "Trusted_Connection=True"
Specifies the Windows authentication.
#### "Microsoft.EntityFrameworkCore.SqlServer"
Provider Name
#### "-OutputDir Models"
Specifies the directory where we want to generate all the classes which is the Models folder in this case.
