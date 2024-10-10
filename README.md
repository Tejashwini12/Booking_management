**# API Testing with pytest**

### Introduction

    Welcome to the API Testing suite! This project uses pytest, a powerful testing framework for Python, 
    to ensure the reliability and correctness of our API endpoints. Our goal is to validate that each API endpoint
    functions as expected and handles various scenarios gracefully.

#### Prerequisites

    Before running the tests, make sure you have all required dependencies installed. 
    The necessary packages are listed in the requirements.txt file. 
    Install them in your virtual environment using:

    pip install -r requirements.txt


##### Configuration 

    Configurations for the testing suite are defined in the conftest.py

    conftest.py: This file contains fixture definitions. Key fixtures include:
    

**##### Project Structure**

#### Data files

    contains the payloads for authentication and booking creation 

##### Src folder

    Request.py: Manages and abstracts the details of making HTTP requests to external services or APIs, 
                facilitating communication between different parts of an application or different services.
    Response.py: Handles HTTP responses, encapsulating details such as status codes

    Manager File: Defines the API endpoints and manages the execution of API calls.
    Management File: Handles responses related to the API calls.

###### Reports folder

    HTML Reports: Generates HTML reports for test results, providing a comprehensive and interactive view of test execution.
    Install pytest-html package 
    pip install pytest-html

###### Test folder

    Test Cases: Contains all the test cases written to validate the API endpoints. 
        Each test case checks specific aspects of the API’s functionality and behavior.


**###### Usage**

    Run Tests: Execute your tests using pytest 

        pytest --html=reports/report.html --self-contained-html --log-cli-level=INFO

        This generates a url open  that url in your browser 
    