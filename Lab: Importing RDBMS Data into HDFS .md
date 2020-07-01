#  Import data from a database into HDFS. 


 1) Import the Table into HDFS 
  a. Enter the following Sqoop command (all on a single line), which imports the  salaries table in the test database into HDFS: 
  
![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/1.PNG)


2) Verify the Import:


![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/2.PNG)

3) Use the cat command to view the contents of the files.

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/3.PNG)

4) Specify Columns to Import 

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/4.PNG)

5) After the import, verify you only have one part‐m file in salaries2:

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/5.PNG)

6) Importing from a Query 
Write a Sqoop import command that imports the rows from salaries in MySQL whose 
salary column is greater than 90,000.00.  

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/6.PNG)

7) To verify the result, view the contents of the files in salaries3. You should have only two output files and View the contents of part‐m‐00000 and part‐m‐00001.  

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/7.PNG)
