Project
================
Test auth application that will use Entity Framework (SqlExpress) as a datastore and AspNetCore Identity for user authentication.  It will generate a bearer token that (as the issuer) which can be used with another API (Audience).

### Install
===========
Make sure to run the EF commands when you open the project.

#### Apply migration 

```powershell
dotnet ef database update
```

#### Create new migration

```
dotnet ef migrations add <migrationName>
```
