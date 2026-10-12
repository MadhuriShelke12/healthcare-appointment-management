
# Manual Test Cases – Healthcare Appointment Management System

## Project Overview
- **Application:** Healthcare Appointment Management System
- **Testing Type:** Manual Testing
- **Application Type:** Front-end web prototype
- **Technologies:** HTML, CSS, JavaScript, localStorage

## Test Execution Results

| Test Case ID | Test Scenario | Actual Result | Status |
|---|---|---|---|
| TC_001 | Launch application | Website opened successfully | PASS |
| TC_002 | Verify page heading | Healthcare Appointment System heading was displayed correctly | PASS |
| TC_003 | Book an appointment | Appointment was added successfully | PASS |
| TC_004 | Submit without patient name | Validation message appeared and submission was prevented | PASS |
| TC_005 | Select a doctor | Selected doctor displayed correctly | PASS |
| TC_006 | Select appointment date | Selected date displayed correctly | PASS |
| TC_007 | Verify appointment details | Entered details matched the appointment list | PASS |
| TC_008 | Multiple appointments | Multiple appointments appeared in the list | PASS |
| TC_009 | Refresh the page | Appointments remained visible after refreshing | PASS |
| TC_010 | Responsive layout | Form remained usable in a narrow browser window | PASS |

## Limitations
- Appointments are stored in the same browser using localStorage.
- There is no backend server or database integration.
- User authentication is not implemented.

## Future Enhancements
- Java backend integration
- SQL database integration
- REST API integration
- User authentication and role-based access
