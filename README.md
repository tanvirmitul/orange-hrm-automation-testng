# orange-hrm-automation-testng

## Scenerio
1. Visit the site: https://opensource-demo.orangehrmlive.com/ 
2. Assert the dashboard 
3. Create 2 new employees (create login details showed on class) 
4. Search the employees with their Id and assert that 2 employees are found 
5. Then login with the last employee credential 
6. Update some employee info (e.g Nationality, Date of Birth) 
7. Now go to my info page and assert the edited info 
8. Finally logout your profile 

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
