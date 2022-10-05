# Dapper All-In-One

This repo is clone of [Dapper](https://github.com/DapperLib/Dapper) +
[Dapper.Contrib](https://github.com/DapperLib/Dapper.Contrib), but merged into one library.
Project is created for .NET Core 6.

## What's changed

* From Dapper.Contrib merged: `Get`, `GetAll`, `Insert`, `Update`, `Delete`
* Added `DeleteByKey` to delete record by primary key
* When table name is inferred from type name, I removed adding suffix "s" - absolutely incorrect logic
* Sign is removed (no need)
