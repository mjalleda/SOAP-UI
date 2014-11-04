2: Project2_Properties_Requirements : 
====================================    
In this project, I covered different type of properties and requirements.  
**1: TestSuite1_Requirements:**   I created three requirements at Project level. Names are  
USD-INR  
AUD-INR  
QAR-INR  
And created a three test cases inside Testsuite1_Requirements and attached these three test cases for the requirements. after you run the suite, the “status for the scope” for the requirement will be changed.

**2: TestSuite2_Properties:** The test case “TestCase_Properties” inside this test suite, shows how   
- how to create a property Step  
- how to create properties  
- How to call/use these properties inside test steps

**Custom Properties & Global Properties:**  
Properties are two types:  
- Custom Properties  
- Global Properties  

**Custom Properties:**   These properties can be defined for Test Cases, For Test Suites & For Projects.  
For example:   
1: Custom properties defined at TestCase level:   
If you define custom properties for a test case “TestCase_ABC”, then you can only use them inside a test case, other test cases can’t use them. 
Custom properties defined at TestSuite level:   
If you define custom properties for a test suite “TestSuite_ABC”, then you can only use them inside a test suite, other test suites can’t use them. 
3: Custom properties defined at project level:   
If you define custom properties for a project “Project_ABC”, then you can only use them inside a project, other projects can’t use them.  

**Global Properties:**   Global properties can be defined/used globally. Which means, you can access/use global property anywhere in SOAP UI projects. Which means, you can use these in   
- any test steps,   
- in any test cases,   
- in any test suites &   
- in different projects too. 

For better understanding, I created some assignments. See below:
**TestSuite2.0_CustomProperties_Using_InDifferentTestSteps:**   Here, I created custom properties for test case “TestCase1_CustomProperties” and used those inside test case. I mean, I used them test steps inside this test case.    
TestStep1:TestRequest1  
TestStep2:TestRequest2 

**TestSuite2.1_CustomProperties_Using_InDifferntTestCases:**   Here, I created custom properties for a test suite and used those inside test suite. I mean, I used them in test cases inside this test suite.  
Test Case1:TestCase1_CustomProperrties  
Test Case2:TestCase2_CustomProperrties 

**TestStuie2.3_CustomProperties_Using_InDiffererntTestSuite_A AND 6:  TestStuie2.3_CustomProperties_Using_InDiffererntTestSuite_B**   
Here, I created custom properties for a project “Project2_Properties_Requirements” and used those inside project. I mean, I used them in test suites inside this project.  
Test Suite1: TestStuie2.2_CustomProperties_Using_InDiffererntTestSuite_A   
Test Suite2: TestStuie2.2_CustomProperties_Using_InDiffererntTestSuite_B

**TestSuite2.4_GlobalProperties_Using_InDifferentTestCases:**  I created global properties and I used them in different test cases: In this TestSuite, I crated Two Test Cases (below) and I called global properties.  
Test Case1: TestCase1_GlobalProperties  
Test Case2: TestCase2_GlobalProperties

**TestSuite2.5_GlobalProperties_Using_InDifferentTestSuites_A & TestSuite2.6_GlobalProperties_UsingInDifferentTestSuites_B:**  
I created global properties and I used them in two different test suites:

**TestSuite2.6_GlobalProperties_Using_InDifferentProject_A & TestSuite2.7_GlobalProperties_Using_InDifferentProject_B**  
I created global properties and I used them in two different projects: Project1 “Project2_Properties_Requirements” & Project2 “Project4_GlobalProperties_GlobalPropertiesTransfers”  
Notes: You will find below test suite inside project “Project4_GlobalProperties_GlobalPropertiesTransfers”  
TestSuite2.7_GlobalProperties_Using_InDifferentProject_B
