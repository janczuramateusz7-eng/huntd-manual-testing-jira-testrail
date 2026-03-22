# Test Plan – Huntd Application

---

## 📌 Project Overview

The purpose of this Test Plan is to define the testing approach and scope for the Huntd application across multiple platforms.

This is a joint test plan covering:
- web application testing in desktop browsers
- web application testing in mobile browsers
- Android mobile application testing

---

## 🎯 Objective

The main objective of testing is to verify that the application:
- meets functional requirements
- provides stable and reliable behavior
- works consistently across supported platforms

Testing focuses on validating core functionality, including:
- user registration and authentication
- session handling and access permissions
- role-based features (Candidate / Recruiter)
- candidate search and filtering
- profile viewing and interactions
- main page behavior

---

## 🧩 Test Items

### Web Application
- URL: https://huntd.tech
- desktop web browsers
- mobile web browsers

### Mobile Application
- Android mobile application

### Out of Scope Platform
- iOS mobile application

---

## 🔍 Scope of Testing

### ✅ In Scope

#### Web Application
- main page for engineers
- main page for recruiters
- registration form
- social registration (Google, LinkedIn, GitHub)
- links to Jobs and Web3 companies
- user feedback section
- mobile app promotion banner

#### Authentication
- user registration
- user login
- social authentication
- logout

#### Candidates List
- display of candidate cards
- "Show experience" functionality
- opening candidate profile in a new tab

#### Filters
- filters visible to all users
- unauthorized users cannot use filters
- authorized users can use filters normally

---

### ❌ Out of Scope

- iOS mobile application
- admin functionality
- question form
- features not available in Android version
- performance testing
- security penetration testing
- backend / API testing

---

## 🧪 Test Approach

### Requirements-Based Testing
Test cases are created based on functional requirements and application modules.  
All features are covered with test cases in TestRail.

### Exploratory Testing
Exploratory testing is performed to detect:
- hidden requirements
- edge cases
- usability issues
- unexpected behavior

### Risk-Based Testing
Priority is given to critical features:
- authentication
- role-based access control
- candidate data visibility
- main user flows

### Mobile Testing
Only features available in the mobile app are tested.  
Unsupported features are excluded.

### Defect Management
All defects are reported in Jira with:
- steps to reproduce
- expected vs actual result
- priority
- screenshots or recordings

---

## 🔎 Test Types

- functional testing
- UI and content testing
- authorization and permission testing
- compatibility testing
- usability testing
- basic security checks

---

## 🛠 Test Environment

### Web Application
- URL: https://huntd.tech
- OS: Windows 11
- Browser: Google Chrome
- Mobile web: Chrome on Android

### Mobile Application
- Android OS: version 13

---

## 👤 Resources

Testing performed by:
- 1 QA Tester (Mateusz Janczura)

---

## ⏱ Effort Estimation

### Web Testing
- test case preparation: 12h
- test execution: 12h
- bug reporting & retesting: 8h

Total: **32h**

### Mobile Testing
- test case preparation: 3h
- test execution: 3h
- bug reporting & retesting: 2h

Total: **8h**

### Total Effort
**40h**

---

## ✅ Entry Criteria

Testing starts when:
- application is accessible
- Android app is available
- requirements are defined
- test plan is prepared
- Jira project is created
- TestRail projects are set up

---

## 🛑 Exit Criteria

Testing is complete when:
- all features have test cases
- all test cases are executed
- all defects are reported
- test execution statistics are prepared

---

## 🐞 Defect Management

All defects are tracked in Jira.

Each bug report includes:
- summary
- environment
- steps to reproduce
- expected result
- actual result
- priority
- screenshots / recordings

---

## 📦 Deliverables

- test plan (web + mobile)
- requirements analysis
- functional decomposition
- Jira project
- TestRail structure (documented)
- permission testing table
- RTM (traceability matrix)
- test execution results
