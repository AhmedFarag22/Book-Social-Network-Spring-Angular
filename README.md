Table of Contents
Overview
Features
Technologies Used
Backend (book-social-network)
Frontend (book-social-network-ui)
Learning Objectives
License
Getting Started
Contributors
Acknowledgments
Overview
Book Social Network is a full-stack application that enables users to manage their book collections and engage with a community of book enthusiasts. It offers features such as user registration, secure email validation, book management (including creation, updating, sharing, and archiving), book borrowing with checks for availability, book return functionality, and approval of book returns. The application ensures security using JWT tokens and adheres to best practices in REST API design. The backend is built with Spring Boot 3 and Spring Security 6, while the frontend is developed using Angular with Bootstrap for styling.

Features
User Registration: Users can register for a new account.
Email Validation: Accounts are activated using secure email validation codes.
User Authentication: Existing users can log in to their accounts securely.
Book Management: Users can create, update, share, and archive their books.
Book Borrowing: Implements necessary checks to determine if a book is borrowable.
Book Returning: Users can return borrowed books.
Book Return Approval: Functionality to approve book returns.
Class diagram
<img width="1019" height="552" alt="class-diagram" src="https://github.com/user-attachments/assets/c0f19cb4-cd01-4a29-8db4-b2752f68f1af" />


Spring security diagram
<img width="1019" height="552" alt="class-diagram" src="https://github.com/user-attachments/assets/77942e2c-9997-4038-b633-fdde6b4721e8" />


Backend pipeline
<img width="2662" height="1126" alt="be-pipeline" src="https://github.com/user-attachments/assets/4ffce3d8-98ab-4fa3-a80f-2a2b43bf03fb" />


Backend pipeline
<img width="2156" height="977" alt="fe-pipeline" src="https://github.com/user-attachments/assets/d0a25ff0-946e-4996-9d99-cf912fda0351" />


Technologies Used
Backend (book-network)
Spring Boot 3
Spring Security 6
JWT Token Authentication
Spring Data JPA
JSR-303 and Spring Validation
OpenAPI and Swagger UI Documentation
Docker
GitHub Actions
Keycloak
Frontend (book-network-ui)
Angular
Component-Based Architecture
Lazy Loading
Authentication Guard
OpenAPI Generator for Angular
Bootstrap
