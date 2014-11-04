Project1_Assertions_TestSteps_Others:
======================================  
This project has below test suites. Basically, it covers most of assertions, Test Steps & Others like (CDATAResponse, Regex, and Attachment).

**1: TestSuite1_Assertions:**  It has single test case but this test case has many test steps. This test suite covers below assertions. I created one test step for each assertion. And there is a test step which has combination of all assertions (Combination).    
Contains    
Not Contains    
InvalidHTTPStatusCodes    
ValidHTTPStatusCodes    
SOAPFault    
SOA   
NotSOAPFault    
SOAPResponse    
SLAResponse    
Combination of all above assertions. 

**2: TestStuite2_XpathAssertion:** In this test suite has a single test case and which tests Xpath Assertions. 
Case: Used Currency Converter and coverting three values from Celsius to Fahrenhite.  
Hence, created three test steps for each value. Each test step has Xpath Assertion, it takes Expected result from “Response” and takes Actual Result from “Defined Properties”  
TestCases: TestCase_XpathAssertion.   
For ex: TestRequest_Convert_CelToFahrenhite_C1: Open this test step. It takes C1 value from property step “TestData_properties”. Xpath Assertion is attached to this test step. Xpath Assertion takes expected result from “Response” & Actual Result from property test step “ExpectedResult_Properties”.

**3: TestSuite3_XpathAssertion_ResponseVerifications:**  In this test suite,I used Xpath Assertion again. And I wanted to validate below three, in DataDriven testing. 
- “Complete Response” (including from SOAP Envelope which is the first line in the Web Service response).  
- Multiple Nodes in the response  
- a single node in the response. 

Solution: To validate above, I created three test steps and each one have its own DataDriven framework (which means, created DataSource, DataSourceLoop & DataSink Steps) with multiple values.

For ex:  
1: TestCase1_CompleteResponseVerification: This one has its own data driven framework and also have Xpath. Xpath gets Actual result from “Web Service response” & Expected result from “DataSource”.    
Xpath verifies complete response.

2: TestCase2_CompleteResponseVerificationMultipleNodesVerifications_OutofCompleteResponse: This one has its own data driven framework and also have multiple Xpath assertions. Xpath assertions gets Actual result from “Web Service response” & Expected result from “DataSource”.    
So each Xpath test one node. 

3: TestCase3_IndividualNodesVerifications_WithIndividualResponse: This one has its own data driven framework and also have Xpath. Xpath gets Actual result from “Web Service response” & Expected result from “DataSource”.    
Xpath verifies single node response.

**TestSuite4_MessageContentAssertion**  
In this suite, you will find two test cases.  
MessageContentAssertion_usedIn_RegularCase: In this test step, you will find MessageContenAssertion, for regular test step. Basically, you will see how this works on regular case.

MessageContentAssertion_usedIn_DataDriverTestCase: In this test step, you will find MessageContenAssertion, for data driven scenario. Basically, you will see how this works on DataDriven scenario.

**TestSuite5_ManualTestStep**  
In this test suite, you will find a case “TestCase_ManualTestStep”, here you will find a dataDriven scenario. Here, I added ManualTestStep. 

**Testsuite6_AssertionTestStep:**  
In this suite, you will find two test cases.   
I wanted to add AssertionTestStep for different assertions (for my test step) and want to check different boolean logic combinations (And & OR), hence created multiple test steps.

**TestSuite7_Attachment:**   In this test suite, you will find a test case. In which test step I attached two attachments. One is with cached and one without caching. and later I’m forwarding my attachment in my test step and expecting a error message in Response. 

**TestSuite8_Regex**  
In this test suite, you  will find a test case “TestCase_RegexExpression1”, which has many Contains assertions, in these assertions I used regular expression for validating the expected with actual result. 

**TestSuite9_CDATA_ListResponse_PropertiesTransfers:**  
In this test suite, you will find  
- How CDATA format look like?   
- How to retrieve values when response contains tables/lists. How to transfer them OR Store them?

