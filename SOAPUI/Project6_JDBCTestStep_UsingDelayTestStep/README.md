Project6_JDBCTestStep_UsingDelayTestStep:
=========================================  
In this assignment, I used my web services.   
Web Service: Very simple, it connects to database and creates, find & delete employee details from database.  
Here, I used JDBC Test Steps for data driven testing.   
Here, I have three test cases.

**TestCase1_ExecuteAllEmployeeOperations_DelayTestStep:**  In tis test case, I’m not using JDBCTestStep, just executing all operation are working correctly with delayteststep.  
- I used DelayTestStep.   
- First I added a employee to Db, then deleted the added employee, and finally finding if employee deleted correctly. 

**TestCase2_ExecuteJDBCRequestStep:**  In tis test case, I’m using JDBCTestStep. Not using DataDrivenFramework. Here,  
- First, I added employee to DB  
- Using JDBCTestStep and finding if employee added correctly by executing DB Queries.   
- Finally, deleting the added employee.

**TestCase3_ExecuteJDBCRequestStep:**  In tis test case, I’m using JDBCTestStep. And also using DataDriven testing. Here,  
- I want to add multiple employee details to Database. Hence, I created excel application with employee details. Now, I used DataSource to retrieve data from excel application.  
- Now, created a test request to add employee to db.  
- Using JDBCTestStep to find whether employee added correctly?  
- Now, putting some wait period before deleting the employee.  
- now deleting the employee.  
- Using DataSourceLoop for DataDrivenFramwork.
