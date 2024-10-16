
# HSTU Online Academic Transcript Distribution System

## Project Report
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

---

## Introduction

In today's fast-paced digital world, efficient academic services are crucial to a university's operations. The need for digitalization of academic transcripts is increasingly becoming essential for universities. This project involves designing and implementing an online system to automate and streamline the distribution of academic transcripts at Hajee Mohammad Danesh Science and Technology University (HSTU). The system is developed using the Agile Software Development Life Cycle (SDLC) to ensure flexibility, transparency, and continuous improvement during the development process.

![photo_2024-10-16_07-28-30](https://github.com/user-attachments/assets/078d94db-1793-4441-9bc8-6d358efc7423)

## Project Vision and Planning

### Requirement Engineering

#### Feasibility Study
![photo_2024-10-16_07-32-55](https://github.com/user-attachments/assets/761a6b05-92f4-4982-8b91-c4b92ab8de8c)
Feasibility studies were carried out in all domains, including technical, economic, and operational aspects.

#### Product Backlog Creation
Key features identified from stakeholder requirements include:
- Student authentication and authorization
- Online request for academic transcripts
- Fee payment integration (if applicable)
- Automated generation and digital signature on transcripts
- Notifications for students (via email/SMS)
- Administrator control panel for managing requests

---

## User Requirements and System Requirements

### User Requirements
#### Student Requirements
- Secure login using university-issued credentials
- Ability to request academic transcripts online
- Payment processing for transcript-related fees (if applicable)
- Status notifications via email or SMS
- Ability to download or receive transcripts digitally once approved

#### Admin Requirements
- Manage transcript requests
- Approve or deny requests
- Generate and distribute transcripts with digital signatures

### System Requirements

#### Functional Requirements
- Secure student login system
- Transcript request form
- Admin dashboard for request management
- Automatic transcript generation and notifications
- Payment integration (if applicable)

#### Non-Functional Requirements
- Data security and encryption
- Scalability and performance under high demand
- Reliability and high availability
- Compliance with data protection standards (e.g., GDPR)
- Usability for both students and admins

---

## Design and Architecture

### Technology Stack
- **Frontend**: React.js, Vue.js
- **Backend**: PHP Laravel for server-side logic
- **Database**: MySQL
- **Security**: Blockchain for authentication
- **Payment Gateway Integration** (if applicable)

### System Architecture
Outline of high-level architecture including backend (student information, transcript data, request statuses) and frontend (student and admin interfaces).

---

## Development (Iterations/Sprints)
![photo_2024-10-16_07-38-49](https://github.com/user-attachments/assets/590cd70b-6ed4-489d-8e24-6fe70e641a8a)
- **Sprint 1**: Basic student login & authentication using secure methods (e.g., OAuth, JWT)
- **Sprint 2**: Transcript request form development
- **Sprint 3**: Admin dashboard for managing requests
- **Sprint 4**: Transcript generation and distribution
- **Sprint 5**: Payment integration (if applicable)
- **Sprint 6**: Final checks

---

## Testing and Feedback
![photo_2024-10-16_07-41-05](https://github.com/user-attachments/assets/2094cacc-93cf-4bea-a2e4-33d2301514f5)

### Unit Testing
- Test student authentication, transcript request form, admin dashboard, and payment gateway.

### Integration Testing
- Ensure seamless connection between modules (login, transcript request, and payment).

### System Testing
- Simulate full workflows and test system load under multiple requests.

### User Acceptance Testing (UAT)
- Feedback from a group of students and admins to fine-tune the system.

### Security Testing
- Ensure proper encryption for authentication and payments.

### Regression Testing
- Re-run all tests after system updates or new feature additions.

---

## Deployment

- Deployed on AWS, Azure, or local HSTU servers with SSL certificates.
- Automate repetitive tasks and ensure consistent environments for development and production.
- Rollback plans in case of deployment issues.

---

## Maintenance and Continuous Improvement

- Monitor system performance, fix bugs, and release updates regularly.
- Address user feedback to improve the system.

---

## Key Benefits of Using Agile for This Project

- **Iterative Approach**: Deliver and test functional parts regularly.
- **Flexibility**: Adapt quickly to changing requirements.
- **Transparency**: Involve stakeholders at every stage to meet their needs.

---

## Conclusion

The development of an online academic transcript distribution system for HSTU using the Agile SDLC offers a solution that is both efficient and user-friendly. The iterative nature of Agile ensures continuous improvement and adaptability to evolving needs. By automating the process, the system saves time for both students and administrative staff, while ensuring the accuracy and security of academic records.

---

## References
- Sommerville, Ian. *Software Engineering* (9th Edition)
- Geeks for Geeks, [Software Engineering Requirements Engineering Process](https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/)
- LucidChart, [Designing Website](https://lucid.app)
- Canva Designing App

