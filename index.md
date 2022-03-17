# General Definitions

- VIEW - store query
- STORED PROCEDURE - script containing query, DDL, and can return tabular data
- USER DEFINED FUNCTION - similar to stored procedure, can return tabular data or value, but cannot affect anything outside the function
- INDEX - structure assisting the database when locating rows
- CONSTRAINTS - rules of a table or column and its data, such as dtype and format
- TRIGGER - stored procedure implemented when something happens in the database
- TYPES - data type of a column
- SEQUENCE - container holding incremental data
- SYNONYM - an alias

2 types of INDEXING
- clustered index
  - stores and organizes table, though less efficient
- non-cluster indexing
  - seperate structure, defined on 1+ columns on the table

# GENERAL QUERY STRUCTURE
`SQL
USE dbname

GO

SELECT *

FROM tbl
`
