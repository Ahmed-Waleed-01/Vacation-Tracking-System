# Vacation-Tracking-System

## 🎯 Vision
A Vacation Tracking System (VTS) will provide individual employees with the 
capability to manage their own vacation time, sick leave, and personal time off, 
without having to be an expert in company policy or the local facility’s leave 
policies

## 📋 Requirements
### Functional Requirements (FRs)
  
1. The system is implemented as an extension to the existing intranet portal system of the company
2. The VTS uses the company portal’s sign-on mechanisms for all authentication.
3. Employees can view their leave balance
4. Employees can access requests made within the previous calendar year
5. Employees can make a request within 18 months of current date.
6. Manager can approve or reject a request.
7. Use e-mail notifications to request manager's approval.
8. Notify employees with e-mail notification upon changing the status of the request.
9. The system keeps log of all transactions.
10. Enables the HR and system administrators to override all actions
restricted by system rules, while logging all of those overrides.
11. Allows managers to directly give personal leave time (within the system-set
limits/rules).
12. Provides a Web interface for other internal systems to query and find any
given employee’s vacation request summary.
13.Interfaces with the legacy HR department systems to retrieve required
employee information and changes.

### Non-Functional Requirements (NFRs)
1. Response time <2s under normal load (Performance).
2. Hashed Passwords, Encrypted data and Role-Based access (Security).
3. Easy to use, clean and simple interface (Usability).
4. 99.9% uptime (Reliability).

## Key Constraints
1. New system must work with old system or existing HR/ERP system.
2. Must keep logs up to 18 months in the past.
3. System must be web only.

