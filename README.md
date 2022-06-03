# Database-Project
The task was to transfer a database from postgresql to oracle with JDBC and DatabaseMetaData

Since i programmed it for only a couple of hours, it still has a couple of problems.

1. Integer Arrays cant be transfered
2. It only works for databases with specific data types, because it was only built for the database i needed to transfer.
3. Issue with constraints and primary keys that are also foreign keys.
