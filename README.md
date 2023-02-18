# orange-hrm-automation-testng
This is a complete project where a Demo site site is automated by writing test suites using selenium-webdriver and TestNg as testing framework.

## Scenerio
1. Visit the site: https://opensource-demo.orangehrmlive.com/ 
2. Assert the dashboard 
3. Create 2 new employees (create login details showed on class) 
4. Search the employees with their Id and assert that 2 employees are found 
5. Then login with the last employee credential 
6. Update some employee info (e.g Nationality, Date of Birth) 
7. Now go to my info page and assert the edited info 
8. Finally logout your profile 

Key test cases(total 19) are written for each module and test suites created including the positive and negative test cases.
A state-transition flow of test-cases are designed and run like an admin can login to the system then admin can create new employee and check the new 
employee list. Then logout from the system. After that login with the new employee email and password and check user information then logout from the site.
For failed test cases it will take a screenshot aswell at the point of failure.
The test runner codes can be extracted from this [link](https://github.com/tanvirmitul/orange-hrm-automation-testng/tree/main/src/test/java/testrunner).</br>
The module test case steps code can be extracted from this [link](https://github.com/tanvirmitul/orange-hrm-automation-testng/tree/main/src/test/java/pages).</br>
The test cases are written following standard test case format in excel file.
View the excel file from this  [link](https://docs.google.com/spreadsheets/d/188TsQ7-0rViwqfXjv0XTk7FRtamZzay7M-Ma-WZjqSc/edit?usp=sharing).

## Technology and Tool Used
- Selenium Webdriver
- TestNG
- Java
- Gradle
- intellij idea 
- Allure


## How to run this project
- clone this project
- hit the following command into the terminal:
  - gradle clean test
- For generating Report in Allure hit
  - allure generate allure-results --clean -o allure-report
  - allure serve allure-results        
 
## Prerequisite
- TestNG,Selenium Webdriver,Java-8 or higher dependencies must be installed

## Video Output:
https://user-images.githubusercontent.com/29010350/202970620-16e4db42-dbb7-4186-8107-188a77a6edba.mp4
