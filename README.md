# Sql Notes And Cheatsheet 

## Coding Standards
1. Use [ ] brackets to specify coloumn name in select statement.
2. Do not use SELECT * as it affects significant performance.
   For. Eg. SELECT **[ID]**
                 **, [NAME]**
                 from Employees;
3. Select query should have SELECT keyword in Capital Letters.
   For. Eg. **SELECT** [ID]
                 , [NAME]
                 from Employees;
4. Specify column name on seperate lines.
   For. Eg. SELECT [ID]
                 **, [NAME]**
                 **, [SALARY]**
                 from Employees;
5. Comma seperator should be before the start of new column name.
   For. Eg. SELECT [ID]
                 **,** [NAME]
                 **,** [SALARY]
                 from Employees;
6. Execution of query should be fast so write query likewise.
7. Proper Indentation should be followed while writing the query.
8. Define Aliases to change column name to your convenient name. Used to shorten Column Names of Coulmns having large names.
9. **'AS'** keyword is used to define aliases.
   For. Eg. SELECT **[Department Name]** AS **[DeptName]**
                   from Employees;
10. First Character of Identifier should start with **(_), (@), #**.
11. Do not use Reserved keywords for identifiers.
12. Not to use embedded special or supplementary characters.
13. When keyword & column name are same use square bracket to use column name in query.
    For. Eg. SELECT [NAME]
                   , **[DATE]** 
                   from Employees;
14. Temporary Table can be created using #, ## or Table Variable.
15. **;** should be specified at the termination of every statement.
16. **;** always required for Common Table Expressions and Service Broker Commands.
