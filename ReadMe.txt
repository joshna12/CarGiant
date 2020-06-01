This is a BDD Page object Model.

In order to run the test on local machine few things need to be noted.
 Java download
 InteliJ Idea download
 Java setup with and requires configuration on the InteliJ Idea
 Maven plugin and Cucumber Plugin needs to be added
 In case of ChromeDriver or other Drivers don't work then it they need to be downloaded .exe path need to
 be provided within the BasePage (scr >> main >> BasePage)
 global.properties path need to be declared within the BasePage

 Project Structure:
 src.main.java.BasePage : Has browser and Driver setup
 src.test.java.features : Has Feature file written in Gherkin format (Given When Then)
 src.test.java.steps : Has feature step_Definitions and Hooks (Before and After Test setup)
 src.test.java.cucumber.Options.TestRunner : All the test will run with cucumber Option.
 In Order to run the particular Test @tagname should be entered.
 src.test.java.pageObjects : Has all the Page Objects methods
 pom.xml : This file has all the required dependencies for the project.

target: It will be generated automatically once test is run. Generated cucumber html report,
screen shots will be stored within this folder

