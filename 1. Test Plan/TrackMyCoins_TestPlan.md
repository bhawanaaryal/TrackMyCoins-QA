## 1. Overview 

### Project Name

TrackMyCoins

### Project Description

TrackMyCoins is a personal finance tracking web application that allows users to manage expenses, categorize transactions, and monitor financial activity through dashboards and summaries.

### Purpose of Testing

The purpose of testing is to verify that the application functions correctly, securely, and reliably while providing accurate transaction management and financial tracking features.

## 2. Scope
### 2.1 Inclusions

The following modules are included in testing:

#### Authentication Module
* User registration
* User login
* Logout functionality
* Session/token validation

#### Expense Management Module
* Add expense
* Edit expense
* Delete expense
* View expense history

#### Budget Management Module
* Add budget
* Edit budget
* Delete budget
* View current budget

#### Category Management
* Create category
* Assign categories to transactions

#### Dashboard Module
* Total expense calculation
* Monthly summaries

#### Validation Testing
* Required fields
* Invalid inputs
* Negative amount handling
* Date validation

### 2.2 Test Environments
* Environment	Details
* Frontend : Angular
* Backend : ASP.NET Core Web API
* Database : SQL Server/MySQL
* Browser : Google Chrome
* OS : Windows 10

### 2.3 Exclusions

The following are excluded from testing:

* Performance testing
* Load testing
* Security penetration testing
* Mobile application testing

## 3. Test Strategy

The application will undergo:

### Functional Testing

To verify that application features behave according to requirements.

### Validation Testing

To ensure invalid or unexpected inputs are handled correctly.

### Regression Testing

To ensure existing functionality continues working after modifications.

### API Testing

APIs will be tested using:

Postman


## 4. Defect Reporting Procedure

Defects identified during testing will be documented with:

Bug ID
Severity
Priority
Steps to reproduce
Expected result
Actual result
Status

Bug reports will be maintained in:

04_Bug_Reports/TrackMyCoins_BugReports.xlsx

## 5. Roles and Responsibilities

QA Tester -> Create test cases, execute testing, report bugs
Developer -> Fix identified defects
Tester/Developer -> Validate fixes and perform regression testing

## 6. Test Schedule

Phase 1:	Test planning and scenario preparation
Phase 2:	Test case creation
Phase 3:	Manual test execution
Phase 4:	Bug reporting
Phase 5:	API testing
Phase 6:	SQL validation
Phase 7:	Regression testing

## 7. Test Deliverables

The following deliverables will be produced:

Test Plan
Test Scenarios
Test Cases
Bug Reports
API Test Collection
SQL Validation Queries
Test Execution Report
Screenshots

## 8. Entry and Exit Criteria
Entry Criteria

Testing will begin when:

application is running successfully
database connection is established
APIs are accessible
Exit Criteria

Testing will conclude when:

major functionalities are tested
critical defects are resolved
regression testing is completed

## 9. Suspension and Resumption Criteria

Testing may be suspended if:

application server becomes unavailable
critical blocking defects prevent further testing

Testing will resume after issues are resolved.

## 10. Tools

Excel/Google Sheets	-> Test documentation
Postman	-> API testing
SQL Server/MySQL -> Database validation
Browser DevTools -> UI inspection
GitHub -> Version control and project hosting



## 11. Approvals
Name	Role
Bhawana Aryal	Developer / QA Tester