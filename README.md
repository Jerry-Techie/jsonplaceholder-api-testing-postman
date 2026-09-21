# User Management API Testing

## Scenario:
Imagine you are testing an API for a website where users can view and manage customer information. Your job as the tester is to: "Verify that the User Management API correctly handles retrieving, creating, updating, and deleting users, including invalid requests and error conditions."

## Overview
This project demonstrates API testing of a User Management
API using Postman.

The testing focused on CRUD operations, positive and negative
test scenarios, status code validation, response validation,
and error handling. 

API- https://jsonplaceholder.typicode.com/users

There is a maximum of 10 Predefined user details that are fetched from the above API.

The API Baseline test suite was executed by creating a workspace in Postman named 'User Management API Baseline Test Suite'. Thereafter, postman collection was created ('jsonplaceholder API'). The execution began by creating my first request (GET) https://jsonplaceholder.typicode.com/users. KIWI TCMS was used to document all test case while also using postman script.

**USER MANAGEMENT API**

 GET Users
TC-001 Get all users
TC-002 Get specific user
TC-003 Get non-existent user

 POST Users
TC-004 Create user

 PUT Users
TC-005 Update user

 PATCH Users
TC-006 Partially update user

 DELETE Users
TC-007 Delete user

**Error-Handling Scenarios**

## Tools Used

1. Postman
2. REST API
3. JavaScript
4. Git and GitHub
5. Kiwi TCMS

## Test Coverage

- GET users
- GET single user
- POST user
- PUT user
- PATCH user
- DELETE user
- Invalid user ID
- Invalid endpoint
- Response status validation
- Response format validation
- Error handling

##Test Results
