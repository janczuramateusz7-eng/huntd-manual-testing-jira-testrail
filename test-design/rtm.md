# Requirements Traceability Matrix (RTM) – Huntd Application

---

## 📌 Overview

This matrix maps functional requirements to corresponding test cases created in TestRail.

---

## 🔗 RTM Table

| ID     | Module               | Requirement                                                                 | Test Case IDs                          |
|--------|----------------------|-----------------------------------------------------------------------------|----------------------------------------|
| RTM-01 | Main Page            | Registration form is displayed for guest users                             | C40                                    |
| RTM-02 | Main Page            | Links to Jobs and Web3 companies are visible                               | C259, C54, C183, C164, C181            |
| RTM-03 | Main Page            | Registration form is hidden for authorized users                           | C185                                   |
| RTM-04 | Main Page            | Role switch is visible                                                     | C44                                    |
| RTM-05 | Main Page            | "For Engineers" view works correctly                                       | C46                                    |
| RTM-06 | Main Page            | Social registration buttons are displayed                                  | C182                                   |
| RTM-07 | Main Page            | Mobile app banner is displayed                                             | C184                                   |
| RTM-08 | Main Page            | Feedback section contains at least 10 comments                             | C55, C109                              |
| RTM-09 | Main Page            | "For Companies" view works correctly                                       | C45                                    |
| RTM-10 | Main Page            | "For Companies" page opens correctly                                       | C49                                    |
| RTM-11 | Main Page            | CEO quotes and partner logos are displayed                                 | C50, C56, C328                         |
| RTM-12 | Main Page            | Comparison section is displayed                                            | C187                                   |
| RTM-13 | Main Page            | Navigation links are visible in header                                     | C329                                   |

---

## 👥 Candidates List

| ID     | Requirement                                                                 | Test Case IDs            |
|--------|------------------------------------------------------------------------------|--------------------------|
| RTM-14 | Subscription form is visible                                                 | C256                     |
| RTM-15 | User can subscribe to vacancies                                              | C257                     |
| RTM-16 | Candidate card shows skills and achievements                                 | C260, C261               |
| RTM-17 | Candidates link is visible for guest                                         | C57                      |
| RTM-18 | Candidate card contains short description                                    | C195                     |
| RTM-19 | "Show experience" displays experience                                        | C201                     |
| RTM-20 | Candidate profile opens in new tab                                           | C198                     |
| RTM-21 | Candidate contacts are hidden for guest                                      | C199                     |
| RTM-22 | Candidate contacts are hidden before chat                                    | C204                     |
| RTM-23 | Experience is sorted correctly                                               | C205                     |
| RTM-24 | Filters are visible                                                          | C127, C189               |
| RTM-25 | Salary filter works correctly                                                | C192, C262, C263         |
| RTM-26 | Guest cannot use filters                                                     | C188                     |
| RTM-27 | Sign in prompt appears on filter hover                                       | C128                     |
| RTM-28 | Role filter works correctly                                                  | C190                     |
| RTM-29 | Technologies filter works correctly                                          | C191                     |
| RTM-30 | English level filter works correctly                                         | C193                     |
| RTM-31 | Location filter works correctly                                              | C194, C264, C265         |
| RTM-32 | Job offers section is displayed                                              | C102, C318               |
| RTM-33 | Jobs link is visible                                                         | C59                      |
| RTM-34 | Jobs link redirects correctly                                                | C60                      |
| RTM-35 | Guest prompted to sign in when adding job manually                           | C123                     |
| RTM-36 | Guest sees limited vacancies                                                 | C118                     |
| RTM-37 | Guest prompted to sign in for 1-Click Apply                                  | C120                     |
| RTM-38 | "View more" prompts login                                                    | C125                     |
| RTM-39 | Authorized user can use filters                                              | C252                     |
| RTM-40 | Authorized user can post jobs (manual / ATS)                                 | C173, C254               |
| RTM-41 | Authorized user sees full vacancies                                          | C167, C103, C319         |
| RTM-42 | Authorized user can apply via 1-Click Apply                                  | C253                     |
| RTM-43 | Additional jobs load after clicking "View more"                              | C176                     |
| RTM-44 | Guest prompted to sign in when using ATS import                              | C299                     |

---

## 💬 Chats

| ID     | Requirement                                                                 | Test Case IDs            |
|--------|------------------------------------------------------------------------------|--------------------------|
| RTM-45 | Chats page is visible for logged-in user                                     | C177                     |
| RTM-46 | Recruiter can start chat                                                     | C179, C180               |
| RTM-47 | Recruiter cannot see contacts before interaction                             | C230                     |
| RTM-48 | "All" tab is default                                                         | C178                     |
| RTM-49 | Candidate can open contacts                                                  | C231                     |
| RTM-50 | Candidate can decline sharing                                                | C232                     |
| RTM-51 | Recruiter can reject chat                                                    | C233                     |
| RTM-52 | User can mark chat as favorite                                               | C235, C267               |
| RTM-53 | User can archive chat                                                        | C234, C268               |

---

## 🔐 Authentication (Sign Up / Sign In)

| ID     | Requirement                                                                 | Test Case IDs            |
|--------|------------------------------------------------------------------------------|--------------------------|
| RTM-54 | User can register with email/password                                       | C269, C270               |
| RTM-55 | User selects role during registration                                       | C206, C258               |
| RTM-56 | Social login works                                                          | C80–C85                  |
| RTM-57 | Sign up link visible on sign in page                                        | C303                     |
| RTM-58 | Password field masks input                                                  | C305                     |
| RTM-59 | Repeat password masks input                                                 | C306                     |
| RTM-60 | Create account works                                                        | C327                     |
| RTM-61 | Candidate can add skills                                                    | C214–C216                |
| RTM-62 | Candidate can add experience                                                | C217                     |
| RTM-63 | Candidate sets salary                                                       | C218, C271–C280          |
| RTM-64 | Candidate selects English level                                             | C219                     |
| RTM-65 | Candidate sets location                                                     | C220, C273, C274         |
| RTM-66 | Candidate adds experience manually                                          | C221                     |
| RTM-67 | Candidate imports experience from LinkedIn                                  | C222                     |
| RTM-68 | Candidate adds achievements                                                 | C223                     |
| RTM-69 | Candidate uploads avatar                                                    | C224                     |
| RTM-70 | Candidate uploads CV                                                        | C225                     |
| RTM-71 | Candidate adds social links                                                 | C226                     |
| RTM-72 | Recruiter role selection works                                              | C207                     |
| RTM-73 | Recruiter enters basic info                                                 | C208                     |
| RTM-74 | Recruiter sets salary                                                       | C210, C275, C276         |
| RTM-75 | Recruiter sets English level                                                | C212                     |
| RTM-76 | Recruiter sets location                                                     | C213, C277, C278         |
| RTM-77 | Recruiter sets experience                                                   | C211                     |
| RTM-78 | Recruiter sets technologies                                                 | C209                     |

---

## 👤 Profile

| ID     | Requirement                                                                 | Test Case IDs            |
|--------|------------------------------------------------------------------------------|--------------------------|
| RTM-87 | Role switching works                                                        | C238                     |
| RTM-88 | Candidate profile activation works                                          | C247–C251                |
| RTM-89 | Profile editing works                                                       | C236, C314, C315, C237   |
| RTM-90 | Social accounts can be connected                                            | C239–C241                |
| RTM-91 | Password change works                                                       | C245, C246               |
| RTM-92 | Profile page opens                                                          | C311                     |
| RTM-93 | Profile summary displayed correctly                                         | C312, C313               |
| RTM-94 | Logout works                                                                | C309, C310               |
| RTM-95 | Recruiter can access hiring management                                      | C316                     |
| RTM-96 | Social connections work                                                     | C242–C244                |

---

## 📎 Footer & Web3

| ID     | Requirement                                                                 | Test Case IDs            |
|--------|------------------------------------------------------------------------------|--------------------------|
| RTM-97 | Social media links are displayed                                             | C130, C281–C286, C326    |
| RTM-98 | Footer information links are displayed                                       | C131, C287, C288, C324   |
| RTM-99 | Feedback section visible                                                     | C107, C320               |
| RTM-100| Feedback list displayed                                                      | C108, C321               |
| RTM-101| Web3 companies page opens                                                    | C111, C325               |
| RTM-102| Top 100 companies displayed                                                  | C110                     |
| RTM-103| Companies list displayed                                                     | C112                     |
| RTM-104| Company entries contain logo and name                                        | C113                     |
| RTM-105| Company list is paginated                                                    | C114                     |
| RTM-106| Company links are clickable                                                  | C115                     |
| RTM-107| Company opens in new tab                                                     | C116                     |
| RTM-108| Company jobs page shows vacancies                                            | C117                     |
