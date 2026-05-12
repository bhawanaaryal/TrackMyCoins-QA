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

Bug ID<br>
Severity<br>
Priority<br>
Steps to reproduce<br>
Expected result<br>
Actual result<br>
Status<br>

Bug reports will be maintained in:

04_Bug_Reports/TrackMyCoins_BugReports.xlsx

## 5. Roles and Responsibilities

QA Tester -> Create test cases, execute testing, report bugs<br>
Developer -> Fix identified defects<br>
Tester/Developer -> Validate fixes and perform regression testing<br>

## 6. Test Schedule

Phase 1:	Test planning and scenario preparation <br>
Phase 2:	Test case creation <br>
Phase 3:	Manual test execution<br>
Phase 4:	Bug reporting<br>
Phase 5:	API testing<br>
Phase 6:	SQL validation<br>
Phase 7:	Regression testing<br>

## 7. Test Deliverables

The following deliverables will be produced:

Test Plan<br>
Test Scenarios<br>
Test Cases<br>
Bug Reports<br>
API Test Collection<br>
SQL Validation Queries<br>
Test Execution Report<br>
Screenshots<br>

## 8. Entry and Exit Criteria
Entry Criteria

Testing will begin when:

Application is running successfully.<br>
Database connection is established.<br>
APIs are accessible.<br>
Exit Criteria

Testing will conclude when:

Major functionalities are tested.<br>
Critical defects are resolved.<br>
Regression testing is completed.<br>

## 9. Suspension and Resumption Criteria

Testing may be suspended if:

Application server becomes unavailable.<br>
Critical blocking defects prevent further testing.<br>

Testing will resume after issues are resolved.

## 10. Tools

Excel/Google Sheets	-> Test documentation<br>
Postman	-> API testing<br>
SQL Server/MySQL -> Database validation<br>
Browser DevTools -> UI inspection<br>
GitHub -> Version control and project hosting<br>



## 11. Approvals
Bhawana Aryal	Developer / QA Tester