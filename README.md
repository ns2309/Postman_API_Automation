# Postman API Automation Framework

This repository contains API automation tests built using Postman and Newman.  
It demonstrates automated testing for REST, GraphQL, SOAP APIs and OAuth2 authentication using Postman collections.

## Technologies Used
- Postman
- Newman
- REST API Testing
- GraphQL API Testing
- SOAP API Testing
- OAuth2 Authentication
- JavaScript Assertions
__________________________________________________________________________________________________________________________________________________________________
## Features

- Collection-based API testing
- Environment-based configuration (QA / UAT)
- Data-driven testing using CSV files
- Command-line execution using Newman
- Automated HTML test reports
____________________________________________________________________________________________________________________________________________________________________________
## Project Structure

collections  
Postman API test collections

environments  
Environment configurations

globals  
Global variables used across collections

data  
CSV files used for data-driven testing

newman  
Generated HTML test reports

___________________________________________________________________________________________________________________________________________________________________
## Run Tests Using Newman
newman run collections/Library.postman_collection.json \
-e environments/UAT.postman_environment.json \
-g globals/Automation_Testing.postman_globals.json \
-d data/BooksData.csv \
-r htmlextra

## HTML reports screenshort
<img width="1391" height="1395" alt="QA_test_report" src="https://github.com/user-attachments/assets/45b04b0d-aa51-4db2-b1cb-708297c1fcc9" />

<img width="1452" height="3654" alt="Test_details" src="https://github.com/user-attachments/assets/68dc5a87-3b85-42a7-837d-ba37a5a1aa5f" />




