Microsoft SQL Driver for YOURLS 1.7.1+
====================

Plugin for [YOURLS](http://yourls.org) `1.7.1+`. 

Description
-----------
This is a custom DB layer that allows YOURLS to use a Microsoft SQL Server (2012+) Database.

This requires YOURLS **1.7.1** just like ozh's SQLite plug-in (if the official 1.7.1 [release](https://github.com/YOURLS/YOURLS/releases) isn't ready yet, that means you'll need to install [current master](https://github.com/YOURLS/YOURLS/archive/master.zip)) and may completely break with the next release

Installation
------------
1. Copy `db.php`, `ez_sql_sqlsrv.php` and `ez_sql_sqlsrv_yourls.php` into the `/user` directory.
2. Create a new database on your SQL Server
3. Setup your config.php as normal with the database credentials, name and hostname
4. Enjoy!

FAQ
-------
##### *Will this break my existing install that uses MySQL?*
No, just like the SQLite driver written by ozh your original database will remain untouched.

License
-------
*"Do whatever the hell you want with it"*.