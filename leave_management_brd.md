# Business Requirements Document (BRD)
## Attendance and Leave Management System

---

# 1. Purpose

The purpose of this system is to provide a centralized platform that enables employees and managers to manage attendance and leave requests efficiently while ensuring accurate tracking of leave allocations and approval workflows.

The system will replace manual or fragmented leave tracking processes with a secure and structured solution.

---

# 2. Objectives

The system aims to:

- Provide employees with a simple way to request time off
- Enable managers to review and approve leave requests
- Ensure accurate tracking of employee leave allocations
- Support organizations operating across multiple countries with different public holidays
- Improve visibility of team availability
- Reduce administrative overhead for HR teams

---

# 3. Scope

## In Scope

- Employee leave request submission
- Manager approval workflows
- Leave allocation management
- Employee and role management
- Holiday calendar management
- Email notifications related to leave requests
- Authentication using Microsoft Single Sign-On
- Web-based access via desktop and mobile devices

## Out of Scope

- Payroll processing
- Integration with external HR or payroll systems
- Native mobile applications
- Advanced leave policies beyond annual allocation

---

# 4. Stakeholders

| Stakeholder | Role |
|---|---|
| Employees | Submit leave requests and view leave balances |
| Managers | Approve or reject leave requests |
| HR Administrators | Manage employee records, allocations, and calendars |
| System Administrators | Manage system configuration and access |
| IT / Engineering | Develop and maintain the system |

---

# 5. Business Requirements

## BR-01 Web-Based System

The system must provide a web-based interface accessible to employees, managers, and administrators for managing leave and attendance.

---

## BR-02 Device Accessibility

The system must support access from both desktop and mobile devices through a responsive web interface.

---

## BR-03 User Authentication

Users must authenticate using Microsoft Single Sign-On (SSO).

---

## BR-04 User and Role Management

The system must support the creation and management of user accounts with role-based access control.

Users may be assigned one or more roles including:

- Employee
- Manager
- HR Administrator
- System Administrator

---

## BR-06 Leave Allocation

Each employee must have an annual leave allocation that is tracked by the system.

Leave allocations must be adjusted based on employment start and end dates where applicable.

---

## BR-07 Leave Request Submission

Employees must be able to request time off by selecting individual days or ranges of days.

The system must support both full-day and half-day leave requests.

Employees may include optional comments when submitting requests.

---

## BR-08 Leave Approval Workflow

Leave requests must be routed to the employee’s assigned manager for review and approval.

Managers must be able to approve or reject requests.

---

## BR-09 Leave Balance Management

The system must maintain and display accurate leave balances for employees, including leave taken and remaining allocation.

---

## BR-10 Holiday Calendars

The system must support multiple holiday calendars to accommodate different countries or regions.

Employees must be assigned to a calendar that determines applicable public holidays.

---

## BR-11 Leave and Holiday Visibility

The system must provide users with a clear view of upcoming employee leave and public holidays to support planning and team availability awareness.

Users must be able to view upcoming leave for employees within the organization.

---

## BR-12 Notifications

The system must send email notifications related to leave requests, including when requests are submitted and when approval decisions are made.

---

# 6. Business Rules

The following rules apply to the system:

- Each employee must be assigned a manager responsible for reviewing and approving leave requests.
- Managers approve leave requests for their direct reports.
- Leave balances must reflect approved leave requests.
- Up to four days leave can be carried from one calendar year to the next.
- Leave requests must not overlap with existing approved leave.
- Public holidays should not be deducted from an employee’s leave allocation.

---

# 7. Success Criteria

The system will be considered successful if it:

- Reduces manual leave tracking processes
- Provides accurate leave balance reporting
- Enables efficient approval workflows
- Is adopted by employees and managers for daily use
