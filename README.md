# SQLiteMaintainer

A console application based on [sqlitemaint](https://github.com/Kulak/sqlitemaint) package algorithm.

Syntax:

    sqlitemaintainer [-db dbName] [-dir dirName] [-backup=false] [-h]

*-db dbName*  
SQLite databse file name.  Default is `sqlite.db`.

*-dir dirName*  
Name of the SQL scripts directory.  Default is `sql`.

*-backup=[true|false]*  
Enables unconditional backup of database file.  Backup is done once on startup even if system is about to update database more than once.  Default is `true`.

*-h*  
Prints a syntax help message.

## Alternative

[GO Lang Migrate](https://github.com/golang-migrate/migrate) supports multiple backends.
