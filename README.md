# Vacation Tracking System (VTS) - System Analysis

## 1. Vision

The **Vacation Tracking System (VTS)** enables employees to efficiently manage their vacation time, sick leave, and personal time off without requiring deep knowledge of company or local leave policies.
The system aims to simplify the leave process, reduce manual effort, and improve overall efficiency.

---

## 2. Functional Requirements

1. The system shall allow managers and HR personnel to validate employee vacation requests.
2. The system shall retrieve and process employee request data.
3. The system shall send email notifications to managers for approval.
4. The system shall integrate with internal systems and HR legacy systems.
5. The system shall maintain activity logs for all transactions.
6. The system shall allow HR and system administrators to override system rules when necessary.
7. The system shall allow managers to grant personal leave within system-defined limits.
8. The system shall provide a web service interface for querying employee vacation summaries.
9. The system shall retrieve employee data and updates from HR legacy systems.

---

## 3. Non-Functional Requirements

* **Usability** 
* **Performance** 
* **Readability** 
* **Security** 

---

## 4. Constraints

### 4.1 Organizational Constraints

* The system must implement a flexible, rules-based approach for validating and verifying leave requests.

### 4.2 System Implementation Constraints

* The system must use existing hardware and middleware.
* The system must be integrated into the existing intranet portal.
* The system must use the portal’s Single Sign-On (SSO) for authentication.
* The system must integrate with HR legacy systems for retrieving and updating employee data.
* The system must provide web service interfaces for other internal systems.

---

## 5. Domain Description

The current vacation approval process requires both manager approval and HR review, resulting in delays and increased operational costs.
The proposed system automates this workflow to improve efficiency, reduce processing time, and optimize resource utilization.

---

## 6. System Actors

### Employee

* Primary user of the system.
* Manages personal vacation, sick leave, and time-off requests.

### Manager

* Has all employee capabilities.
* Approves or rejects employee requests.
* Grants personal or compensatory leave within defined limits.

### Clerk (HR Staff)

* Maintains and updates employee records.
* Has permissions to view, add, and modify employee data.
* Uses role-based access with separate login credentials.

### System Admin
* Manages technical infrastructure (e.g., web server, database).
* Handles system logs, including collection, monitoring, and archiving.
* Ensures system availability, performance, and security.

---

## 7. Summary

The Vacation Tracking System streamlines leave management by automating request submission, validation, and approval workflows while ensuring integration with existing organizational systems.

---

## 8. Source of the Example

The **Vacation Tracking System (VTS)** presented in this document is adapted from an example in
*Object-Oriented Analysis and Design with Applications* (3rd Edition),
specifically from Chapter 12.



