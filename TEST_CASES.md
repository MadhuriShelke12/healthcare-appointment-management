# Manual Test Cases – Healthcare Appointment Management System

## Project Overview
- Application: Healthcare Appointment Management System
- Testing Type: Manual Testing
- Application Type: Front-end prototype

## Test Execution Results

| Test Case ID | Test Scenario | Actual Result | Status |
|---|---|---|---|
| TC_001 | Launch application | Website opened successfully | PASS |
| TC_002 | Verify page heading | Not yet recorded | PENDING |
| TC_003 | Book an appointment | Appointment was added successfully | PASS |
| TC_004 | Submit without patient name | Validation message appeared; submission was prevented | PASS |
| TC_005 | Select a doctor | Selected doctor displayed correctly | PASS |
| TC_006 | Select appointment date | Selected date displayed correctly | PASS |
| TC_007 | Verify appointment details | Entered details matched the appointment list | PASS |
| TC_008 | Multiple appointments | Multiple appointments appeared before refresh | PASS |
| TC_009 | Refresh the page | Appointments remained visible after refreshing | PASS |
| TC_010 | Responsive layout | Form remained usable in a narrow browser window | PASS |

## Limitations
- Appointments are saved in the same browser using localStorage.
- Backend, API and database integration are not implemented.
- Authentication is not implemented.

## Future Enhancements
- Java backend
- SQL database
- REST API integration
- User authentication
