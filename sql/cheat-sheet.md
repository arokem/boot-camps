SQL Cheat Sheet
===============

Basic queries
-------------

Select one or more columns:

```sql
SELECT column_name_1, column_name_2 FROM table_name;
-- Only column_name_1 and column_name_2 will be 
-- included in the result.
```

Select every column:

```sql
SELECT * FROM table_name;
-- Every column will be included in the result,
-- indicated by the wildcard (*)
```

Get only unique rows:

```sql
SELECT DISTINCT column_name FROM table_name;
-- The DISTINCT keyword places a constraint
-- on the query, limiting it to unique rows.
```

Perform calculations within a query:

```sql
SELECT column_name_1, ROUND(column_name_2 / 1000.0) FROM table_name;
-- Here, ROUND() and / are function calls.
```

Filtering
---------

Select only the data meeting certain criteria:

```sql
SELECT * FROM table_name WHERE column_name = 'Hello World';
-- Note the use of a single equals sign, unlike many
-- programming languages which use two to compare values.
```

Combine conditions:

```sql
SELECT * FROM table_name WHERE (column_name_1 >= 1000) AND (column_name_2 = 'A' OR column_name_2 = 'B');
```

Sorting
-------

Sort results using `ASC` for ascending order or `DESC` for descending order:

```sql
SELECT * FROM table_name ORDER BY column_name_1 ASC, column_name_2 DESC;
```

Aggregation
-----------

Combine data into groups and calculate combined values in groups:

```sql
SELECT column_name_1, SUM(column_name_2), COUNT(*) FROM table_name GROUP BY column_name_1;
```

Joins
-----

Join data from two tables together:

```sql
SELECT * FROM table_name_1 JOIN table_name_2 ON table_name_1.column_name = table_name_2.column_name;
```

Combining commands
------------------

SQL commands can be combined in the following order:
`SELECT`, `FROM`, `JOIN`, `ON`, `WHERE`, `GROUP BY`, `ORDER BY`.
