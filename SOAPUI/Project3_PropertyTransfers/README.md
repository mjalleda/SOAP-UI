Project3_PropertyTransfers:
===========================  
In this project, I covered different type of property transfers.  

**TestSuite1_PropertiesTransfer:** The test case “TestCase1_PropertyTransfer” inside this test suite, shows how   
- how to create a propertyTransfer Step?  
- how to create properties inside this step?  
- How to call/use these properties inside test steps?

**Custom PropertyTransfer & GlobalPropertytransfers:**  
PropertyTransfers are are two types:  
- Custom Properties transfers  
- Global Properties Transfers  
Custom Properties Transfers: These properties can be defined for Test Cases, For Test Suites & For Projects.  
For example:   
1: Custom property defined defined at TestCase level:   
If you define this property for a test case “TestCase_ABC”, then you can only use them inside a test case, other test cases can’t use them. 
Custom property transfer defined at TestSuite level:   
If you define this properties for a test suite “TestSuite_ABC”, then you can only use them inside a test suite, other test suites can’t use them. 
3: Custom property transfer defined at project level:   
If you define this properties for a project “Project_ABC”, then you can only use them inside a project, other projects can’t use them.  

**Global Properties transfer:**   Global properties can be defined/used globally. Which means, you can access/use global property anywhere in SOAP UI projects. Which means, you can use these in   
- any test steps,   
- in any test cases,   
- in any test suites &   
- in different projects too. 

For better understanding, I created some assignments. See below:  
**TestSuite2_UsingCustomPropertyTrasnfer_DefinedForTestCase_UsedInTestStpes:**   Here, I created custom propertytransfers for a test case “TestCase1_UsingCustomPropertyTransfer_TestCaseLevel” and used those inside this test case. I mean, I used them test steps inside this test case.    
TestStep1:TestStep1_CurrencyConvertion 
TestStep2:TestStep2_TempartureConvertion 

**TestSuite3_UsingCustomPropertyTrasnfer_DefinedForTestSuite_UsedInTestCases:**  Here, I created custom properties for a test suite and used those inside test suite. I mean, I used them in test cases inside this test suite.  
Test Case1:TestCase1_UsingCustomProperrtyTransfer_TestSuiteLevel  
Test Case2:TestCase2_UsingCustomProperrtyTransfer_TestSuiteLevel 

**TestSuite4_UsingCustomPropertyTrasnfer_DefinedForProject_UsedInTestSuites_A AND
TestSuite5_UsingCustomPropertyTrasnfer_DefinedForProject_UsedInTestSuites_B**  
Here, I created custom properties for a project “Project3_PropertiesTransfer” and used those inside project. I mean, I used them in test suites inside this project.  
Test Suite1: TestSuite4_UsingCustomPropertyTrasnfer_DefinedForProject_UsedInTestSuites_A  
Test Suite2: TestSuite4_UsingCustomPropertyTrasnfer_DefinedForProject_UsedInTestSuites_B 

**TestSuite6_GlobalPropertiesTransfers_InBetweenTwoSteps:**  I created global properties and I used them in different test steps to transfer properties: In this TestSuite,I created two test steps and transferred global properties.  
Test Step1: CurrencyConverter  
Test Step2: CelsiusToFahrenhite

**TestSuite7_UsingGlobalPropertiesTransfers_InBetweenTwoTestCases:**  I created global properties and I used them in different test cases to transfer properties: In this TestSuite, I crated Two Test Cases (below) and I called global properties.  
Test Case1: TestCase1  
Test Case2: TestCase2

**TestSuite8_GlobalPropertiesTransfers_InDifferentTestSuites_A and
TestSuite9_GlobalPropertiesTransfers_InDifferentTestSuites_B:**  
I created global properties and I used them in two different test suites:

**TestSuite10_GlobalPropertiesTransfer_InDifferentProject_A & TestSuite2_GlobalPropertiesTransfer_InDifferentProject_A**  
I created global properties and I used them in two different projects: Project1 “Project3_PropertiesTransfers” & Project2 “Project4_GlobalProperties_GlobalPropertiesTransfers”  
Notes: You will find below test suite inside project “Project4_GlobalProperties_GlobalPropertiesTransfers”  
TestSuite2_GlobalPropertiesTransfer_InDifferentProject_B
