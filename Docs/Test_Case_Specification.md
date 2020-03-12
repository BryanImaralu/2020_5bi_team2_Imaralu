# Test Case Specification

# For

# PCTO Application

March 10, 2020


Prepared by: Team 2


 ### 1 Revision History

| **Version** | **Date** | **Name** | **Description** |
| --- | --- | --- | --- |
| 1 | 9/03/2020 | Bryan Imaralu | Initial Document |
| 2 | 10/03/2020 | Bryan Imaralu | Updated test case, login using spaggiari credentials |

---

 ### 2 Introduction

This document provides the test cases to be carried out for the Team2&#39;s PCTO Application.  Each item to be tested is represented by an individual test case.  Each case details the input and expected outputs.

---

 ### 3 Test Cases: PCTO Application

- | Test ID | 1.0 |
| --- | --- |
| Title | Correct Login |
| Feature | Login to Anagrafica PCTO App |
| Objective | Confirm that proper user id and password yields access to the website as expected. |
| Setup | Computer or mobile phone ready to run PCTO application. |
| Test Data | Login informationUser Id = [S12Y909](mailto:cdbpc@umkc.edu)Password = golden |
| Test Actions | 1. Access PCTO/login.php page2. Enter login information3. Login confirm |
| Expected Results | System displays PCTO web application with option to logoff.  Displayed table match the database with companies data umkc.ManageMyID.com. |



- | Test ID | 1.1 |
| --- | --- |
| Title | Incorrect Password |
| Feature | Login to Anagrafica PCTO App |
| Objective | Confirm that valid user id with an invalid password denies access to the website without leaving the user stranded. |
| Setup | Computer or mobile phone ready to run PCTO application. |
| Test Data | Correct user e-mail, incorrect passwordUser Id = S12909YPassword = goldenboys |
| Test Actions | 1 Access PCTO/login.php page2. Enter invalid login information3. Login denied |
| Expected Results | System allows the user to re-enter login credentials |

- | Test ID | 1.2 |
| --- | --- |
| Title | Incorrect User E-Mail |
| Feature | Login to Anagrafica PCTO App |
| Objective | Confirm that invalid user id denies access to the website without leaving the user stranded. |
| Setup | Computer or mobile phone ready to run PCTO application. |
| Test Data | Incorrect user Id, incorrect passwordUser Id = S49912YPassword = goldenboys |
| Test Actions | 1. Access PCTO/login.php page2. Enter invalid login information3. Login denied |
| Expected Results | System allows the user to re-enter login credentials. |
