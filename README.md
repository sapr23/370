# Test Plan

*This is the template for your test plan. The parts in italics are concise explanations of what should go in the corresponding sections and should not appear in the final document.*

**Author**: Greenhorn

## 1 Testing Strategy

### 1.1 Overall strategy

*This section should provide details about your unit-, integration-, system-, and regression-testing strategies. In particular, it should discuss which activities you will perform as part of your testing process, and who will perform such activities.*

 - **Unit Testing:** In unit testing, each module will be tested separately. We will test each module manually by writing test cases for each module. We will compare the results of each module with the expected result to ensure all the module run properly. Software
   engineer will perform the unit testing.
 - **Integration Testing:** In intergration testing, we will test multiple module work as expected. Integration test will expose  defects in the interfaces and the interactions between integrated components. Both QA engineer and software engineer will perform the integration test.
 - **System Testing:** System testing will be performed on the complete program. In the system testing process we will verify all the requirement the app can fulfill. Black box testing will be performed in system testing process. QA engineer will perform the system testing after building the complete app.
 - **Regression testing:** In regression test process, we will check if modifying code has any impact on the outcome. Both QA engineer and software engineer will perform the integration test.

### 1.2 Test Selection

*Here you should discuss how you are going to select your test cases, that is, which black-box and/or white-box techniques you will use. If you plan to use different techniques at different testing levels (e.g., unit and system), you should clarify that.*

 - In unit testing and regression testing, we will use white box testing. We will test each module seperately to check if the module
   give the correct output.
 
 - Black box testing will be used in system tesing process. We will test if the app work properly, what are the requirement the app can
   fulfill etc.

### 1.3 Adequacy Criterion

*Define how you are going to assess the quality of your test cases. Typically, this involves some form of functional or structural coverage. If you plan to use different techniques at different testing levels (e.g., unit and system), you should clarify that.*


### 1.4 Bug Tracking

*Describe how bugs and enhancement requests will be tracked.*
 - We will check each module. If there is error in a module, we can easily identify the error. This is the least costly of all the testing.
 - We will test the interconnection between the integrated units. If all the module pass the unit test but failed in the integration test, we know there is a error while we connect them.
 - During the system testing, if it fails to fulfill the requirement like crash the app or do not work properly we track the error.
 -   We will enlist all the bugs during the testing and notify the project manager.

### 1.5 Technology

*Describe any testing technology you intend to use or build (e.g., JUnit, Selenium).*

-JUnit


## 2 Test Cases

*This section should be the core of this document. You should provide a table of test cases, one per row. For each test case, the table should provide its purpose, the steps necessary to perform the test, the expected result, the actual result (to be filled later), pass/fail information (to be filled later), and any additional information you think is relevant.*
| Purpose |Steps  |Expected Result  |Actual result |pass/fail |Additional Information
|--|--|--|--|--|--|
| The app open properly |Open the app  |open the app without crashing  |  |  |
User can create a list  |User create a list	|A list should appear in the app
|User can delete alist |
