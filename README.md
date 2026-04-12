# Vacation Tracking System (VTS) - System Analysis

## 1. Project Overview

The Vacation Tracking System (VTS) is the first project in a 6-month Node.js mentorship program.  
The goal of this phase is to analyze and design the system before implementation.

---

## 2. Vision

The **Vacation Tracking System (VTS)** enables employees to manage their vacation time, sick leave, and personal time off in a simple and efficient way, without needing deep knowledge of company leave policies.

The system aims to:
- Simplify leave requests and approvals
- Reduce manual HR operations
- Improve workflow efficiency
- Ensure proper integration with internal systems

---

## 3. Functional Requirements

The system shall:

- Allow employees to submit vacation, sick leave, and personal leave requests.
- Enable managers and HR personnel to review and validate requests.
- Send email notifications to managers for approval actions.
- Integrate with internal HR and legacy systems to retrieve and update employee data.
- Maintain logs for all system activities and transactions.
- Allow administrators and HR staff to override system rules when necessary.
- Allow managers to approve limited personal leave within defined policies.
- Provide APIs or web services for querying employee leave summaries.

---

## 4. Non-Functional Requirements

The system must ensure:

- **Usability:** Simple and intuitive interface for all users.
- **Performance:** Fast processing of requests and responses.
- **Security:** Protected access using authentication and role-based authorization.
- **Maintainability:** Clean and structured system design for easy updates and scaling.

---

## 5. System Constraints

### Organizational Constraints
- The system must comply with company policies and HR rules regarding leave management.

### Technical Constraints
- Must use existing infrastructure and middleware.
- Must integrate with the company intranet portal.
- Must use Single Sign-On (SSO) for authentication.
- Must integrate with legacy HR systems.
- Must expose web services for internal system communication.

---

## 6. Domain Description

The current leave approval process requires manual validation by both managers and HR, which leads to delays and increased operational effort.

The proposed system automates this workflow by:
- Digitizing leave requests
- Streamlining approval processes
- Reducing processing time
- Improving operational efficiency

---

## 7. System Actors

### Employee
- Submits and manages personal leave requests.

### Manager
- Reviews and approves/rejects employee leave requests.
- Can grant limited personal or compensatory leave.

### HR Clerk
- Maintains employee records.
- Views, adds, and updates employee information.
- Operates with role-based access control.

### System Administrator
- Manages system infrastructure and configurations.
- Monitors logs and system performance.
- Ensures system availability, security, and reliability.

---

## 8. Summary

The Vacation Tracking System (VTS) is designed to automate and streamline employee leave management by integrating request handling, approval workflows, and HR systems into a unified platform.

---

## 9. Reference

This system analysis is adapted from:
*Object-Oriented Analysis and Design with Applications (3rd Edition), Chapter 12*



