
# Kiran Rera -  Fancode Assignment

This is a small automation framework for ensuring that the users in Fancode city have completed more than 50% of their tasks based on their ToDos.

## Prerequisites
Before using this framework, ensure that you have following installed on you machine:

* Java Development Kit (JDK)
* Maven Build tool
* Eclipse or IntelliJ any Integrated Development Environment (IDE) 

## Getting Started 


1. Clone the repository on local machine
  ```console
git clone https://github.com/ (** Need To Add)
```
2. Open the project in your preferred IDE

3. Build the project using Maven to resolve the dependencies

## Running Test 
To run the automted test, follow these steps

Navigate to src/test/java/com.assignment.fancode > FancodeTest.java > Right Click on the file and Click run as TestNG test.

4. Test results will be displayed in the console, including Passes, Fail and Skips and any assertions.

5. ExtentReport will be generated for the result with logs 

## About the framework
### Test Data 🗃️
  com.assignment.constants :
  * Config file in framework contains the Base URI
  * Constants has the constants for Longitude and Latitude
  * StatusCodeEnum stores the API status codes for now, later it may be implemented to add messages as well
 
### Test Configurations 
 com.assignment.core :
  * Client file contains the Response get method, we can implement more methods further
  * TestBase cotains the setUp method to set the BASE_URI

### Test API Endpoints 
 com.assignment.endpoints: This contains all the Endpoints mentioned


## Tools and Technologies used 💻
* Rest Assured
* TestNG
* Maven
* Extent Reports
* Eclipse
* Jackson API
* Java






