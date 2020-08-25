## Shawn Dawkins
### 08-22-2020
### Foundations of Database: Module 07 Functions
### https://github.com/SCDawkins/DBFoundations-Module07


_1.	Explain when you would use a SQL UDF:_
User Defined Functions: SQL Server allows us to create our functions called as user defined functions in SQL Server. For example, if we want to perform some complex calculations, then we can place them in a separate function, and store it in the database. Whenever we need the calculation, we can call it. There are three types of SQL user defined functions: Scalar, Inline & Multi-statement.

_2. Explain are the differences between Scalar, Inline, and Multi-Statement Functions._

   Scalar Function: It is a function that returns a single value. Generally, we must define the function body between BEGIN … END block, but for inline scalar function, you can 
   omit them. We can use any SQL data type as the return type except text, image, next, cursor, and timestamp.

   Table Valued Functions: It is a user defined function in SQL Server that returns a table.
   Inline Table valued Functions: This function returns a table data type based on a single SELECT Statement

   A multi-statement table-valued UDF returns a row-set populated by two or more T-SQL statements from within the UDF.  The internal rows-sets are concatenated into a table 
   variable for output from the UDF. 

_Conclusion_ 

   We can use UDF statements that can pull the same information from a database without rewriting the sane code every time.



Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SCDawkins/DBFoundations-Module07/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
