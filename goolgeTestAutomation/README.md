GoogleSearch Exercise

All Steps are executed as per the given 'alfresco exercise.xlsx’ and Displays Pass or fail in ExtentReports.
Executed Steps are also shown in Console or terminal


1. Test Cases from 'alfresco exercise.xlsx’ is updated into GoogleResults.xlsx sheet under folder> data in order to create a Hybrid Framework.
i.e. data > GoogleResults.xlsx
2. Download the project for Github
	- Extract into workspace
3. To execute the project via shell/command-line/terminal using Maven Commands, follow below steps

	- Navigate to the unzipped folder
    - Goto Terminal and run below commands to execute code from shell/command-line/terminal

	- mvn clean
	- mvn compile
	- mvn clean test -DsuiteXmlFile=testng.xml 
	
	(this will execute the Testcases and display the results within terminal)
	
	- Goto Project folder and refresh in order to update ExtentReports folder with latest test result file, Created with Name "Date & time" that includes detailed Reports in HTML format
	
4. To execute the project into preferred IDE, please import the project after making the Project maven compatible with preferred IDE.
i.e. example for Eclipse
		- mvn clean
		- mvn eclipse:eclipse
		- Goto Eclipse and import the project.
	In order to execute the project,  
	 
	a. To Run as TestNG Suite: Goto /src/test/resources/testng.xml & right click "testng.xml" & run as "TestNG Suite"
	
	b.  To Run as TestNG Test: GO-TO /src/test/java/qa/alfresco/google/testcases & right click 	"GoogleSearchTestRunner" & run as "TestNG Test"
	
	
5. ExtentReports are generated and stored under ExtentReports folder. Please refresh the project to update this folder with the reports after running TestSuites or TestCases. 
	
--------------------------------------------------



