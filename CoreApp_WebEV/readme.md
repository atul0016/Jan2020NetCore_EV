System.ComponentModel.DataAnnotations.dll
- Provides attribute class for
	Mapping to Class property to DB Table for IdentityKey
	Validation Attribute classes
		RequiredAttribute, CompareAttribute, RegExAttribute, EmailAttribute
		DataTypeAttribute, etc
=============================================================================================
Create a Data Acees Technology
The Entity Framework Core 3.1 (EF Core), the cross-platform, lightweight Data Access ORM Technology
Strategies for ORM on EF Core
1. Database First Approach
2. Code First Approach

Install-Package Microsoft.EntityFrameworkCore.Design

Install-Package Microsoft.EntityFrameworkCore.SqlServer
 
Install-Package Microsoft.EntityFrameworkCore.Tools –Pre
 
Install-Package Microsoft.EntityFrameworkCore.SqlServer.Design

Microsoft.EntityFrameworkCore Package
	DbContext, DbSet<T>, DbContextOptions<DbContext>

DbContext
1. Connect to Database Server
2. Map the Model classes from Application to Database Table using DbSet<T>
	Where T is the Model class name that mapes with Database Table of name T
3. Commit Transactions using SaveChanges() and SaveChangesAsync() methods