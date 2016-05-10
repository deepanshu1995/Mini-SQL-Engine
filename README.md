csvSQL

Running Instructions:
$ python test.py

Implemented Features:
 - 'show tables' command to show table names present in the DB
 - 'delete' command can delete multiple rows. Also, the where clause handles conditions other than '=' as well
 - '>=' can be replaced by 'ge' in where clause. Other in/equality conditions can also be replaced by their string equivalents
 - 'where' clauses can handle column-column, column-integer, integer-column or integer-integer comparisons
 - Error reporting for ambiguous column names and where clauses.# Mini-SQL-Engine
