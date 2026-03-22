Test Plan

Objective
The purpose of this Test Plan is to define the testing approach and scope for the Huntd application across multiple platforms.

This is a joint test plan covering:

Web application testing in desktop browsers,
Web application testing in mobile browsers
Android mobile application testing.

The main objective of testing is to verify that the application meets the requirements and provides stable, reliable, and consistent behavior across supported platforms.

Testing will focusing on validating the core functionality, including:

User registration and authentication,
Session handling and basic access permissions, 
Features available to each role (candidate and recruiter),
Searching and filtering candidates,
Viewing candidate profiles and simple interactions,
Checking the main page content and how it behaves.

Test Items 

The following applications and platforms are included in the testing scope:

Web Application
URL https://huntd.tech
Desktop web browsers
Mobile web browsers


Mobile Application
Android mobile application


Out of Scope Platform
iOS mobile application


Scope
3.1. In Scope

Testing will cover the following functional areas

Web application
Main page for engineers
Main page for recruiters
Registration form
Social registration (Google, LinkedIn, GitHub)
Links to Jobs and Web3 companies
User feedback section
Mobile app promotion banner for authorized users

Authentication
User registration
User login
Social authentication
Logout

Candidates List
Displays of candidate cards
“Show experience” functionality
Opening candidate profile in a new tab

Filters
Filters  section is visible to all users
Unauthorized users cannot use filters 
Authorized users can see filters normally


3.2. Out of Scope

The following items are excluded from testing:
iOS mobile application
Admin functionality
Question form
Things that are not included in the Android version
Performance testing
Security penetration testing
Backend/API testing










Test Approach

Requirements-based testing
Test cases will be created based on the available functional requirements and application modules. 
All application features will be covered with test cases in TestRail.

Exploratory testing
In addition to the prepared test cases, exploratory testing will be performed. The goal is to find issues related to hidden requirements, edge cases, usability and unexpected system behavior.

Risk-based prioritization
Testing will focus first on the features that are most important for the system.
authentication
role-based access control
candidate profile access and data visibility
main use flows

Mobile testing approach
Testing of the Android app will include only the features that are available in                    the mobile version.
Missing or unsupported features will not be included in test cases or Jira.

Defect management
All found defects will be reported in Jira.
Each bug report will include steps for reproduce, expected and actual results, priority and screenshots or recordings. 



Test Types
 The project will include the following types of testing:

Functional Testing 
Checking if the main features of the application work according to the requirements. This includes testing login, candidate search, filters, viewing profiles, and other key user actions. 

UI and Content Testing 
Checking if the user interface looks correct and all elements are visible. This includes verifying banners, feedback sections, logos, and other static content on the landing page.

Authorization and Permission Testing
Verifying that users can only access features allowed for their role. This includes restrictions for unauthorized  users and visibility of sensitive data.
Compatibility Testing 
Testing the application on different supported environments:
Desktop web browsers
Mobile web browsers
Android devices

	Usability Testing
	Checking if the application is easy to use - navigation, user flows, and overall clarity.

	Basic Security Checks
	Ensuring that restricted areas cannot be accessed without logging.


Test Environment

	Testing will be performed in the following environments 

	Web Application
Test URL: https://huntd.tech
Operating System: Windows 11
Desktop browser: Google Chrome 144
Mobile web testing: Chrome browser on Android devices

Mobile Application (Android)
Android OS version 13


Resources

Testing will be performed by:
1 QA Tester (Mateusz Janczura)

	Effort Estimation
	Web Testing
Test cases preparation and review: 12 hours
Test execution: 12 hours
Bug reporting and retesting: 8 hours

Total Web testing effort: 32 hours 

Mobile Testing
Test cases preparation and review: 3 hours
Test execution: 3 hours
Bug reporting and retesting: 2 hours

	Total Mobile testing effort: 8 hours

	Total Effort
	Total estimated testing effort: 40 hours


Entry Criteria / Exit Criteria 

Entry Criteria

Testing will start when the following conditions are met:
Access to the web application is available,
Access to the Android application is provided,
Requirements have been met,
The Test Plan is prepared,
Jira project is created,
TestRail projects for Web and Mobile are set up.

	Exit Criteria

	Testing will be considered complete when:
All web features in scope have test cases,
All web test cases are executed in TestRail,
All implemented Android features have test cases,
All found defects are reported in Jira,
Test execution statistics are prepared,
Defect Management

All defects found during testing will be reported and tracked in Jira
Each bug report will include:
a short summary of the issue
the environment
steps to reproduce
expected result
actual result
priority
screenshots, recordings

Deliverables
	All following testing documents and outputs will be created during the project:
Test Plan for Web and Android
Requirements Analysis
Functional decomposition
Jira project
TestRail project
Permission Testing Table
Requirements Traceability Matrix
Test execution results in TestRail


