---

# 📱 Mobile Application RTM

---

## 📌 Overview

This section covers requirements and test cases for the mobile application (Android).

---

## 🔗 RTM Table – Mobile

| ID     | Module     | Requirement                                             | Test Case IDs |
|--------|------------|----------------------------------------------------------|---------------|
| RTM-109 | Main Page  | App launches successfully for logged-out user           | C330          |
| RTM-110 | Main Page  | Sign In screen is accessible                            | C331          |
| RTM-111 | Main Page  | Homepage is displayed for logged-in user                | C337          |
| RTM-112 | Main Page  | User session remains active after login                 | C336          |

---

## 🔐 Authentication

| ID     | Requirement                                              | Test Case IDs |
|--------|-----------------------------------------------------------|---------------|
| RTM-113 | User can sign in with valid credentials                  | C289          |
| RTM-114 | Error message for invalid email format                   | C332          |
| RTM-115 | Error message for invalid credentials                    | C290          |
| RTM-116 | Sign In blocked for empty fields                         | C333          |
| RTM-117 | Error for unregistered email                             | C334          |
| RTM-118 | User can sign in with Google                             | C298          |
| RTM-119 | Successful registration with valid data                  | C335          |

---

## 👤 Profile

| ID     | Requirement                                              | Test Case IDs |
|--------|-----------------------------------------------------------|---------------|
| RTM-120 | User can switch between recruiter and candidate profiles | C297          |
| RTM-121 | Role switching works correctly                           | C340, C339    |
| RTM-122 | User can edit profile information                        | C295, C348    |
| RTM-123 | Contact information section is accessible                | C342, C343    |
| RTM-124 | User can modify and save preferences                     | C344, C345    |
| RTM-125 | User can log out                                         | C347, C346    |

---

## 💬 Chats

| ID     | Requirement                  | Test Case IDs |
|--------|------------------------------|---------------|
| RTM-126 | Chats page opens             | C291          |
| RTM-127 | User can open conversation   | C293          |
| RTM-128 | User can archive chat        | C294          |
