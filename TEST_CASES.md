
# Manual Test Cases – Healthcare Appointment Management System

## Project Overview
- Application: Healthcare Appointment Management System
- Testing Type: Manual Testing
- Application Type: Front-end prototype

## Test Cases

| Test Case ID | Test Scenario | Steps | Expected Result |
|---|---|---|---|
| TC_001 | Launch application | Open the website URL | Website opens successfully |
| TC_002 | Verify page heading | Check the page heading | Correct heading is displayed |
| TC_003 | Book an appointment | Enter valid details and click Book Appointment | Appointment appears in the list |
| TC_004 | Empty patient name | Submit without entering the patient name | Validation prevents invalid submission |
| TC_005 | Select a doctor | Choose a doctor from the dropdown | Selected doctor is displayed |
| TC_006 | Select appointment date | Choose a valid date | Selected date is displayed |
| TC_007 | Verify appointment details | Book an appointment and check the list | Entered details are displayed correctly |
| TC_008 | Multiple appointments | Book two appointments | Both appointments are displayed |
| TC_009 | Refresh the page | Book an appointment and refresh | Observe whether the appointment remains |
| TC_010 | Responsive layout | Open the website in a narrow browser window | Form remains usable |

## Execution Status
## Execution Results

| Test Case ID | Actual Result | Status |
|---|---|---|
| TC_001 | Website opened successfully | PASS |
| TC_003 | Appointment booking succeeded | PASS |
| TC_004 | Empty patient name was rejected | PASS |
| TC_005 | Doctor selection worked correctly | PASS |
| TC_006 | Appointment date displayed correctly | PASS |
| TC_007 | Appointment details matched the entered data | PASS |
| TC_008 | Multiple appointments appeared before refreshing | PASS |
| TC_009 | Appointment disappeared after refresh | Known limitation |
| TC_010 | Form remained usable in a narrow browser window | PASS |

**Note:** Appointments are not saved permanently in the current front-end prototype. Persistent storage is a future enhancement.

TC_002 (page heading) still needs a separate check if you haven't verified it.

## Limitations
This is a front-end prototype. Backend, API and database testing are not yet implemented.
