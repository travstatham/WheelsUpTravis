# WheelsUpTravis
Automated Selenium Test and API tests

1. The Exercise 1 myScript.sh resides in WheelsUpTravis/src/main/java/bash 

2. The Exercise 2 Selenium Automation test resides in WheelsUpTravis/src/test/java/WheelsUpTest.WheelsUpTravis/TestWheelsUp.java

3. The Exercise 3 API Response test for Social Media Accounts is also in the above file, it is the second @Test in the file.

The project uses: Selenium, TestNG, Jackson, Hamcrest, Apache HTTPComponents

There may be a need to import TestNG into the project to get it to work. TestNG is in the Maven pom.xml file, 
but after cloning the project locally, there was an error when opening the project - which was fixed by hovering 
on the error and selecting Add TestNG. I used Version Eclipse 2019-06. 
I had to add the TestNG link to the marketplace and then install the plugin. I'm hoping this is runnable and is
not an issue. 

Run 'TestWheelsUp.java' with TestNG and there should be no failures. 

I also put chromedriver on the classpath and included it in the project. 




Wheels Up
Automation Test Exercise
Exercise 1 - Create a small bash script (name it myScript.sh)
- Create a folder (myFiles)
- Inside the created folder, create 7 files (Eg. file1.txt, file2.txt, file3.txt….)
- After creating 7 files, delete all files except the last 3 files. (After running the command,
file5, file6, and file7 must be still there.)
- Delete the files based on the time it was created


Exercise 2 - Write an automated test with selenium webdriver Java TestNG/JUnit(IntelliJ)
based framework for the following scenario. (Use Page Object Model pattern and Java)
- Navigate to https://wheelsup.com
- Find and print out in the console the following title “A Revolution Has Taken Flight”
- Scroll to the bottom, print out phone number, email(Contact Us), and address(Find Us)
- Scroll to top
- Header menu, click “MEMBERSHIP OPTIONS” and then “CORE MEMBERSHIP”
- Scroll to section “Becoming a Wheels Up Core Member is easy”
- Print out “ONE-TIME INITIATION FEE”
- Scroll to “Learn more today” section (Enter first and last name)
- Click continue
- Enter all the information required to complete the form (/request-info) - DO NOT SUBMIT
- Click “X” at the top right corner


Exercise 3 - Api testing (use any library or framework) - Java
- Create a method called “verifySocialAccounts(String twitter, String instagram)”
- Twitter “https://twitter.com/WheelsUp”
- Instagram “http://instagram.com/wheelsup8760”
- Use this endpoint (https://marketingapi.wheelsup.com/api/initial-data/)
- Get the JSON response and parse it
- Verify if passed social accounts matches the fields from the JSON response (Use any
class assert)

Note: All 3 exercises must be part of one maven project. Upload to your personal Github
account. For exercise 2 and 3, use Java and make sure there’s no dependency failures
when opening from a different machine. We must be able to download it and run with no
issues. For exercise 1, you can just add the code inside a text file.
