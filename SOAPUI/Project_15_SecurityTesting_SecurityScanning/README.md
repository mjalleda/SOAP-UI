Project15_SecurityScanning:
=============================    
This is also interesting assignment. In this assignment, you will many test request under stress test step. Basically, i created different security scanners according to my request.   

**SecurityTest1_SQLInjection_DBEmployeeAdd:** In this test step, I created SQLInjection scanner for “company” filed. And I also added below twp assertions to it.    
- Sensitive Information Exposure    
- Schema Compliance    
- Plus I added more token for testing company field.

**SecurityTest2_InvalidScan_DBEmployeeAdd:** In this test step, I created Invalid Type Scanner for “name” filed. And I also added a assertions to it.  
- Sensitive Information Exposure

**SecurityTest3_FuzzyScan_DBEmployeeAdd:** In this test step, I created Fuzzy Scanner for “name” filed. And I also added below assertions to it.  
- Sensitive Information Exposure

**SecurityTest4_XpathInjection_DBEmployeeAdd:** In this test step, I created Xpath Ijection Scanner for “salary” filed. And I also added below assertions to it.  
- Sensitive Information Exposure

**SecurityTest5_BoundaryTest_CurrencyConvertion:** In this test step, I created Boundary Scanner for both “From” & “To” fileds. And I also added below assertions to it.  
- Sensitive Information Exposure  
- Schema Compliance

**SecurityTest6_BoundaryScan_DBEmployeeAdd:** In this test step, I created Boundary Scanner for both “salary” & “Experience” fileds. And I also added below assertions to it.  
- Sensitive Information Exposure  
- Scema compliance

**SecurityTest7_MalFormedXML_CurrencyConvertion:** In this test step, I created MalFormed XML Scanner for both “From” & “To” fileds. And I also added below assertions to it.  
- Sensitive Information Exposure  
- Schema Compliacne

**SecurityTest8_XMLBomb_CurrencyConvertion:** In this test step, I created XMLBomb for both From & TO fields. And I also added below assertion to it.  
- Sensitive Information Exposure
