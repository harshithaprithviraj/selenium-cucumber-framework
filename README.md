# Selenium-Cucumber BDD Test Automation Framework

This is a **Selenium-Cucumber BDD** framework using the **Page Object Model (POM)** and **JUnit/TestNG** for scalable and maintainable UI test automation. The framework includes data-driven tests using Excel.

## Project Structure

📁 factory - Contains the BaseClass for WebDriver setup
📁 hooks - Contains hooks for setup/teardown
📁 pageObjects - Page Object classes for each page of the app
📁 stepDefinitions - Cucumber step definitions for scenarios
📁 testRunner - Runner class to execute tests
📁 utilities - Utility classes (e.g., DataReader, ExcelUtility)
📁 testData - Excel data files for data-driven tests


## Features
- Cucumber BDD with Gherkin syntax
- Page Object Model (POM) for maintainable code
- Data-driven testing with Excel
- Supports JUnit/TestNG
- Hooks for setup and teardown
- Easy to scale for large test suites

## Running the Tests

### From Command Line:
```bash
mvn clean test
From IDE:
Run TestRunner.java directly in your IDE.

License
This project is open-source and available under the MIT License.
