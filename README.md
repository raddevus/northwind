### Simple sqlite project used to do queries & learn joins

Obtained creation of schema and initial data from : https://en.wikiversity.org/wiki/Database_Examples/Northwind/SQLite

However, I altered the schema of all tables so that each one has a primary identity named ID.<br>
In the original schema they are named ProductId, SupplierID etc. and that is unnecessary.

#### create.txt 
create.txt  - This file contains the entire schema and all the data to load all tables.

to create the schema follow these steps:

1. $ sqlite3 northwind.db  -- creates empty db with filename nortwind.db and starts sqlite3
2. sqlite> .read create.txt  -- reads the entire create.txt and runs it (creates all tables & loads them
3. sqlite> .schema -- displays the schema to verify it loaded properly.

