
# HSTU Online Academic Transcript Distribution System

## Level-3 Semester-I Project Report
**Course Code**: CSE 305  
**Course Title**: Software Engineering  

**Submitted by**  
Amit Hasan Sikder (ID: 2102043)  

**Submitted to**  
Pankaj Bhowmik  
Lecturer, Department of CSE  

Department of Computer Science and Engineering  
Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200

---

## Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Project Vision and Planning](#project-vision-and-planning)
- [User Requirements and System Requirements](#user-requirements-and-system-requirements)
- [Design and Architecture](#design-and-architecture)
- [Development (Iterations/Sprints)](#development-iterations-sprints)
- [Testing and Feedback](#testing-and-feedback)
- [Deployment](#deployment)
- [Maintenance and Continuous Improvement](#maintenance-and-continuous-improvement)
- [Key Benefits of Using Agile for This Project](#key-benefits-of-using-agile-for-this-project)
- [Conclusion](#conclusion)
- [References](#references)

## Figures
- Project Goals/Objectives Triangle
- Step by Step Planing for SDLC
- All types of Feasibility Study
- User role in University
- Question-1
- Question-2
- Question-3
- Question-4
- Question-5
- Question-6
- Question-7
- Question-8
- ER Diagram for System
- Sprint Serial
- Testing Phase
- Suggested Software Development

## Tables
 - Test Case 1
 - Test Case 2
 - Test Case 3
 - Test Case 4
 - Test Case 5
 - Complexity

---

## Abstract

The project report titled "Creating an Online Academic Transcript Distribution System for Hajee Mohammad Danesh Science and Technology University (HSTU)" outlines the design and implementation of a system that automates the distribution of academic transcripts. Developed using the Agile Software Development Life Cycle (SDLC), the system enhances the efficiency and accessibility of transcript services for both students and administrators. Key functionalities include secure student authentication, online transcript requests, payment processing, and automated transcript generation with digital signatures.

The system architecture integrates a front-end user interface for students and administrators, a back-end database for managing transcript data, and features such as email and SMS notifications. Security, scalability, and user experience are prioritized, with the use of blockchain for authentication and data protection.

Agile's iterative approach enables flexibility and continuous improvement throughout the project. Testing phases ensure the reliability and security of the system, including unit, integration, system, and user acceptance testing. The final deployment follows a structured process, including performance monitoring and a rollback plan.

By streamlining transcript distribution, this system is expected to save time and reduce the administrative burden at HSTU while ensuring secure and accurate academic record handling. The report concludes that modern software engineering practices can significantly enhance university services, providing a user-friendly and efficient solution.

---

## Introduction

In today's fast-paced digital world, efficient academic services are crucial to a university's operations. The need for digitalization of academic transcripts is increasingly becoming essential for universities. This project involves designing and implementing an online system to automate and streamline the distribution of academic transcripts at Hajee Mohammad Danesh Science and Technology University (HSTU). The system is developed using the Agile Software Development Life Cycle (SDLC) to ensure flexibility, transparency, and continuous improvement during the development process.

![photo_2024-10-16_07-28-30](https://github.com/user-attachments/assets/078d94db-1793-4441-9bc8-6d358efc7423)
## Fig 1.1 Project Goals/Objective Triangle
---

## Project Vision and Planning
![photo_2024-10-16_20-19-38](https://github.com/user-attachments/assets/92649823-a2d2-4014-997b-7d1530c38f52)
## Fig 2.1 Step by Step Planing for SDLC

### 2.1 Requirement Engineering

#### 2.1.1 Feasibility Study
![photo_2024-10-16_07-32-55](https://github.com/user-attachments/assets/761a6b05-92f4-4982-8b91-c4b92ab8de8c)
## Fig 2.2 All types of Feasibility Study
Feasibility studies were carried out in all domains, including technical, economic, and operational aspects.

#### 2.2 Product Backlog Creation
Key features identified from stakeholder requirements include:
- Student authentication and authorization
- Online request for academic transcripts
- Fee payment integration (if applicable)
- Automated generation and digital signature on transcripts
- Notifications for students (via email/SMS)
- Administrator control panel for managing requests



## 2.3 User Requirements and System Requirements

### 2.3.1 User Requirements
#### 2.3.1(a) Student Requirements
- Secure login using university-issued credentials
- Ability to request academic transcripts online
- Payment processing for transcript-related fees (if applicable)
- Status notifications via email or SMS
- Ability to download or receive transcripts digitally once approved

#### 2.3.1(b) Admin Requirements
- Manage transcript requests
- Approve or deny requests
- Generate and distribute transcripts with digital signatures

### 2.3.2 System Requirements

#### 2.3.2(a) Functional Requirements
- Secure student login system
- Transcript request form
- Admin dashboard for request management
- Automatic transcript generation and notifications
- Payment integration (if applicable)

#### 2.3.2(b) Non-Functional Requirements
- Data security and encryption
- Scalability and performance under high demand
- Reliability and high availability
- Compliance with data protection standards (e.g., GDPR)
- Usability for both students and admins

## 2.4 Requirement Elicitation
### 2.4.1 Requirement Elicitation Technique Apply(Survey/Questionnaire)
 -  Survey(Close-Ended) Link: https://docs.google.com/forms/d/e/1FAIpQLScOocRsYNOBFUCrXKw5-0LncaTc8EF4_HUF_1I7ihcfhxUFyg/viewform
### **Survey Result**
![Picture1](https://github.com/user-attachments/assets/e36874d1-7210-43e4-86c3-3ea3883b387a)
## Fig 2.3 User Role in University
![Question1](https://github.com/user-attachments/assets/5ec58533-0626-4f61-8df1-35ed0a7f07c9)
## Fig 2.4 Survey Question-1
![Question2](https://github.com/user-attachments/assets/be8e8970-6559-44c6-8afa-f07620b87033)
## Fig 2.5 Survey Question-2
![Question3](https://github.com/user-attachments/assets/9a3e15e6-ebc2-4a61-8e25-6591ff096961)
## Fig 2.6 Survey Question-3
![Queston4](https://github.com/user-attachments/assets/4a5e5dd3-b8ee-4708-800e-3e09df78730d)
## Fig 2.7 Survey Question-4
![Question5](https://github.com/user-attachments/assets/4fb160e0-75dc-4b3f-a62e-275531ce92eb)
## Fig 2.8 Survey Question-5
![Question6](https://github.com/user-attachments/assets/ce5cd078-80c5-41f6-a228-06e6f0eb1a0b)
## Fig 2.9 Survey Question-6
![Question7](https://github.com/user-attachments/assets/ec9219cc-cbfc-41eb-9d3b-d4d726c1dcd7)
## Fig 2.10 Survey Question-7
![Question8](https://github.com/user-attachments/assets/796904ab-d91a-4bde-81c7-b0b054aad5e0)
## Fig 2.11 Survey Question-8

--- 

## Design and Architecture

![Screenshot (415)](https://github.com/user-attachments/assets/2a8ca0a2-3b13-4b80-bdd3-a072b8cfdb7b)
## Fig 3.1 ER Diagram for System


### 3.1 Technology Stack
- **Frontend**: React.js, Vue.js
- **Backend**: PHP Laravel for server-side logic
- **Database**: MySQL
- **Security**: Blockchain for authentication
- **Payment Gateway Integration** (if applicable)

### 3.2 System Architecture
Outline of high-level architecture including backend (student information, transcript data, request statuses) and frontend (student and admin interfaces).

---

## Development (Iterations/Sprints)

![photo_2024-10-16_07-38-49](https://github.com/user-attachments/assets/590cd70b-6ed4-489d-8e24-6fe70e641a8a)
## Fig 4.1 Sprint Serial
- **Sprint 1**: Basic student login & authentication using secure methods (e.g., OAuth, JWT)
- **Sprint 2**: Transcript request form development
- **Sprint 3**: Admin dashboard for managing requests
- **Sprint 4**: Transcript generation and distribution
- **Sprint 5**: Payment integration (if applicable)
- **Sprint 6**: Final checks

---

## Testing and Feedback
![photo_2024-10-16_07-41-05](https://github.com/user-attachments/assets/2094cacc-93cf-4bea-a2e4-33d2301514f5)
## Fig 5.1 Testing Phases

### 5.1 Unit Testing
- Test student authentication, transcript request form, admin dashboard, and payment gateway.

### 5.2 Integration Testing
- Ensure seamless connection between modules (login, transcript request, and payment).

### 5.3 System Testing
- Simulate full workflows and test system load under multiple requests.

### 5.4 User Acceptance Testing (UAT)
- Feedback from a group of students and admins to fine-tune the system.

### 5.5 Security Testing
- Ensure proper encryption for authentication and payments.

### 5.6 Regression Testing
- Re-run all tests after system updates or new feature additions.

### 5.7 Test Cases

### 5.7.1 Student Authentication
- Tester: Amit
- Test Date: 2024-08-05
- Objective: Verify if student can log in securely using valid credentials.

## Table 5.1 Test Case 1

| **Test ID** | **Pre-Condition**                                                                                   | **Steps**                                                                                                                                       | **Test I/P**                              | **Test Outcome**                                            | **Actual Result** | **Pass** |
|-------------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|------------------------------------------------------------|-------------------|----------|
| T101        | The student must be registered with a valid university-issued ID and credentials.                     | 1. Open the login page. <br> 2. Enter a valid university-issued ID and password. <br> 3. Click on the login button.                            | Username: 2102043 <br> Password: 1234     | The student should be logged in and redirected to their dashboard. | Logged in          | Pass     |

### 5.7.2 Transcript Request
- Tester: Amit
- Test Date: 2024-09-10
- Objective: Test if a student can request a transcript successfully.
  ## Table 5.2 Test Case 2

| **Test ID** | **Pre-Condition**                                      | **Steps**                                                                                                               | **Test I/P**                                  | **Test Outcome**                                             | **Actual Result**          | **Pass** |
|-------------|---------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|---------------------------------------------------------------|----------------------------|----------|
| T102        | The student must be logged into their account.          | 1. Navigate to the transcript request page. <br> 2. Fill in the required details (graduation year, number of copies, etc.). <br> 3. Submit the request. | Username: 2102043 <br> Session: 2021 <br> Number of copies: 2 | The request should be submitted, and the student should receive a confirmation message. | Submitted successfully     | Pass     |
### 5.7.3 Admin Approval/Denial
- Tester: Amit
- Test Date: 2024-09-22
- Objective: Verify if an admin can approve or deny transcript requests.
  ## Table 5.3 Test Case 3

| **Test ID** | **Pre-Condition**                                     | **Steps**                                                                                                                                  | **Test I/P**                                   | **Test Outcome**                                              | **Actual Result**  | **Pass** |
|-------------|--------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|----------------------------------------------------------------|--------------------|----------|
| T103        | The admin must be logged into the dashboard.           | 1. Navigate to the request management page. <br> 2. Select a pending request. <br> 3. Approve or deny the request.                         | Admin ID: Admin001 <br> Request ID: TRQ-123 <br> Action: Approve/Reject | The system should update the request status and notify the student. | Notify status       | Pass     |

### 5.7.4 Payment Processing
- Tester: Amit
- Test Date: 2024-09-25
- Objective: Verify if an admin can approve or deny transcript requests.
  ## Table 5.4 Test Case 4

| **Test ID** | **Pre-Condition**                                                | **Steps**                                                                                                           | **Test I/P**                                        | **Test Outcome**                                                        | **Actual Result**           | **Pass** |
|-------------|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|------------------------------------------------------------------------|-----------------------------|----------|
| T104        | The payment gateway must be integrated, and the student must have a valid payment method. | 1. Submit a transcript request that requires a fee. <br> 2. Enter payment details and submit the payment.          | Request ID: TRQ-123 <br> Payment Method: Mobile Banking/Card <br> Amount: 10 | The payment should be processed successfully, and the request status should be updated. | Payment successfully | Pass     |

### 5.7.5 Transcript Download
- Tester: Amit 
- Test Date: 2024-10-22
- Objective: Verify if an admin can approve or deny transcript requests.
  ## Table 5.5 Test Case 5

| **Test ID** | **Pre-Condition**                                                | **Steps**                                                                                                           | **Test I/P**                                        | **Test Outcome**                                                        | **Actual Result**           | **Pass** |
|-------------|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|------------------------------------------------------------------------|-----------------------------|----------|
| T104        | The payment gateway must be integrated, and the student must have a valid payment method. | 1. Submit a transcript request that requires a fee. <br> 2. Enter payment details and submit the payment.          | Request ID: TRQ-123 <br> Payment Method: Mobile Banking/Card <br> Amount: 10 | The payment should be processed successfully, and the request status should be updated. | Payment successfully | Pass     |




---

## Deployment

- Deployed on AWS, Azure, or local HSTU servers with SSL certificates.
- Automate repetitive tasks and ensure consistent environments for development and production.
- Rollback plans in case of deployment issues.

---

## Maintenance and Continuous Improvement

- Monitor system performance, fix bugs, and release updates regularly.
- Address user feedback to improve the system.

##  **7.1 Time and Space Complexity (Approximately):**

## Table 7.1 Complexity

| **Time Complexity**  | **O(n), where n is the number of students or transcript requests.** |
|----------------------|---------------------------------------------------------------------|
| **Space Complexity** | **O(n), where n represents the number of students, transcript requests, or blockchain entries.** |



---

## Key Benefits of Using Agile for This Project

- **Iterative Approach**: Deliver and test functional parts regularly.
- **Flexibility**: Adapt quickly to changing requirements.
- **Transparency**: Involve stakeholders at every stage to meet their needs.

---

## Conclusion

The development of an online academic transcript distribution system for HSTU using the Agile SDLC offers a solution that is both efficient and user-friendly. The iterative nature of Agile ensures continuous improvement and adaptability to evolving needs. By automating the process, the system saves time for both students and administrative staff, while ensuring the accuracy and security of academic records.

![photo_2024-10-16_07-43-17](https://github.com/user-attachments/assets/595760a3-21e4-47b9-a411-664e3ab9bc17)
## Fig 9.1 Suggested Software Development
--- 

## References
- Survey Link: https://docs.google.com/forms/d/e/1FAIpQLScOocRsYNOBFUCrXKw5-0LncaTc8EF4_HUF_1I7ihcfhxUFyg/viewform
- Sommerville, Ian. *Software Engineering* (9th Edition)
- Geeks for Geeks, [Software Engineering Requirements Engineering Process](https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/)
- LucidChart, [Designing Website](https://lucid.app)
- Canva Designing App


