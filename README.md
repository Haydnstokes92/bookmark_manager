### To set up the database

 Connect to `psql` and create the `bookmark_manager` database:

 ```
 CREATE DATABASE bookmark_manager;
 ```

 To set up the appropriate tables, connect to the database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.

To view bookmarks, navigate to `localhost:3000/bookmarks`

User would like to keep a record of the most frequently visited websites, using a bookmark system.