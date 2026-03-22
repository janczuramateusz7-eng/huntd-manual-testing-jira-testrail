# Permission Testing Table – Huntd Application

---

## 📌 Overview

This table defines access permissions for different user roles in the Huntd application.

---

## 👥 Roles

- Guest (unauthorized user)
- Candidate (authorized user)
- Recruiter (authorized user)

---

## 🔐 Main Access

| Feature              | Guest | Candidate | Recruiter |
|---------------------|-------|-----------|-----------|
| Access main page    | Yes   | Yes       | Yes       |
| Register account    | Yes   | No        | No        |
| Login               | Yes   | No        | No        |
| Logout              | No    | Yes       | Yes       |

---

## 🔑 Authentication and Account

| Feature                                     | Guest | Candidate | Recruiter |
|---------------------------------------------|-------|-----------|-----------|
| Email registration                          | Yes   | No        | No        |
| Social registration (Google, LinkedIn, GitHub) | Yes | No        | No        |
| Access Sign In page                         | Yes   | Yes       | Yes       |
| Forgot password                             | Yes   | Yes       | Yes       |

---

## 👤 Candidates List

| Feature                   | Guest | Candidate | Recruiter |
|---------------------------|-------|-----------|-----------|
| View candidates list      | No    | Yes       | Yes       |
| View candidate card       | No    | Yes       | Yes       |
| Open candidate profile    | No    | Yes       | Yes       |
| View filters              | Yes   | Yes       | Yes       |
| Use filters               | No    | Yes       | Yes       |

---

## 📄 Candidate Profile

| Feature                            | Guest | Candidate | Recruiter |
|------------------------------------|-------|-----------|-----------|
| View profile information           | No    | Yes       | Yes       |
| View candidate contacts            | No    | No        | Yes*      |

\* After approval

---

## 💬 Chat

| Feature                | Guest | Candidate | Recruiter |
|------------------------|-------|-----------|-----------|
| Start chat             | No    | Yes       | Yes       |
| Receive chat request   | No    | Yes       | Yes       |
| Accept / reject chat   | No    | Yes       | Yes       |
| Archive chat           | No    | Yes       | Yes       |

---

## 🧑‍💼 Candidate Features

| Feature                               | Guest | Candidate | Recruiter |
|----------------------------------------|-------|-----------|-----------|
| Candidate onboarding                   | No    | Yes       | No        |
| Edit own profile                       | No    | Yes       | No        |
| Activate / deactivate profile          | No    | Yes       | No        |

---

## 🏢 Recruiter Features

| Feature                  | Guest | Candidate | Recruiter |
|---------------------------|-------|-----------|-----------|
| Access recruiter mode     | No    | No        | Yes       |
| Add new job               | No    | No        | Yes       |
| Manage candidates         | No    | No        | Yes       |

---

## 💼 Jobs / Web3 Companies

| Feature                | Guest        | Candidate | Recruiter |
|------------------------|--------------|-----------|-----------|
| View job listings      | Yes (limited) | Yes       | Yes       |
| Apply for job          | No           | Yes       | Yes       |
| Filter jobs            | Yes (limited) | Yes       | Yes       |
| Subscribe for vacancies| Yes          | Yes       | Yes       |

---

## 📱 Mobile App

| Feature                | Guest | Candidate | Recruiter |
|------------------------|-------|-----------|-----------|
| Access mobile features | Yes   | Yes       | Yes       |
| Profile settings       | No    | Yes       | Yes       |
| Chat                   | No    | Yes       | Yes       |

---

## 🧪 Testing Notes

During testing, the following were verified:
- role-based access control works correctly
- unauthorized users cannot access restricted features
- sensitive data is properly protected
- feature availability matches user role
