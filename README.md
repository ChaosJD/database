# How to prevent SQL-Injections

## Prepared Statements
* [prepared Statements](http://tutorials.jenkov.com/jdbc/preparedstatement.html)
* [prepared Statements too](https://www.javatpoint.com/java-jdbc)
* minimal rights for sql-user
* no systemaccounts for database-user
* install web application firewall
* white List Input Validation

## Stored Procedures
* [Stored Procedures](https://www.w3schools.com/sql/sql_stored_procedures.asp)
* installed by the db
* **NO** dynmaic generated code
* client references procedure and passes parameters
* parameter tpyed variables


## Neutralisation of sql metacharacters
* **important** identify all Metacharacters
* double quotes
* doubles Backslash
* encapsulate resulting strings in new quotes
* functions check the nuermic input
