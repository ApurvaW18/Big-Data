## 1) Create a new directory in HDFS named salarydata and Put salarydata.txt into the salarydata directory in HDFS. 
![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/9.PNG)


## 2)Check whether the file is created on hdfs

![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/8.PNG)


## 3)Export the Data 

   a. Run a Sqoop command that exports the salarydata folder in HDFS into the  salaries2 table in MySQL. 
   At the end of the MapReduce output, you should see a log event stating that 10,000 records were exported.
    
![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/10.PNG)



   b.Verify it worked by viewing the table’s contents from the mysql prompt. The 
   output should look like the following: 




![](https://github.com/ApurvaW18/devops-course/blob/master/lab%203.1/11.PNG)


    
    
