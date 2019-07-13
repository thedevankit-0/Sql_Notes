# Sql Notes And Cheatsheet 

## Coding Standreds
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
