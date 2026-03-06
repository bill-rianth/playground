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


# 4. Business Rules

The following rules apply to the system:

- Each employee must be assigned a manager responsible for reviewing and approving leave requests.
- Managers approve leave requests for their direct reports.
- Leave balances must reflect approved leave requests.
- Up to four days leave can be carried from one calendar year to the next.
- Leave requests must not overlap with existing approved leave.
- Public holidays should not be deducted from an employee’s leave allocation.


