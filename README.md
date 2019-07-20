# Sql Notes And Cheatsheet 

## Coding Standards
1. Use [ ] brackets to specify coloumn name in select statement.
2. Do not use SELECT * as it affects significant performance.
   For. Eg. 
   ```sql
   SELECT * from Employees;
   ```
3. Select query should have SELECT keyword in Capital Letters.
   For. Eg. **SELECT** [ID]
                      , [NAME]
                 from Employees;
4. Specify column name on seperate lines.
   For. Eg. 
   ```sql
              SELECT [ID]
                 **, [NAME]**
                 **, [SALARY]**
                 from Employees;
   ```
5. Comma seperator should be before the start of new column name.
   For. Eg. 
   ```sql
            SELECT [ID]
                 **,** [NAME]
                 **,** [SALARY]
                 from Employees;
    ```
6. Query should be optimize for better performance.
7. Proper Indentation should be followed while writing the query.
8. Define Aliases to change column name to your convenient name. Used to shorten Column Names of Coulmns having large names.
9. **'AS'** keyword is used to define aliases.
   For. Eg. 
   ```sql
   SELECT **[Department Name]** AS **[DeptName]**
                   from Employees;
                   ```
10. First Character of Identifier should start with **(_), (@), #**.
11. Do not use Reserved keywords for identifiers.
12. Not to use embedded special or supplementary characters.
13. When keyword & column name are same use square bracket to use column name in query.
    For. Eg. 
    ``` sql
               SELECT [NAME]
                   , **[DATE]** 
                   from Employees;
                   ```
14. Temporary Table can be created using #, ## or Table Variable.
15. **';'** should be specified at the termination of every statement.
16. **';'** always required for Common Table Expressions and Service Broker Commands.
17. Code must contain comments.
18. Remove unwanted code.
19. Entity name should be plural.
20. Primary key should be NOT NULL  AND AUTO_INCREMENT.
21. While inserting values in table 
      1. Don't insert the value of auto incremented columun.
      2. Inserting values should be in same case it means data should be consistant.
22 .While creating table obey all the rules of Normal Forms.
23 .Explicitly specify the order of column Like ASC or DESC.
24 .View name should start with 'V'
    Ex.[vEmployee]
25. Schema should be required for tables.
26. All predefine clauses name sholud be in capital letters.
    Ex.FROM,SELECT etc.
   
