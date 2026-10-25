# Test Plan — Appointment Booking Web Application

## 1. Project Overview

Manual functional testing of the public Easy!Appointments demo, covering service/provider selection, appointment date/time, customer information, confirmation summary, and successful registration.

## 2. Objective

Evaluate the booking workflow, document test results, and identify scenarios requiring further testing.

## 3. Test Environment

- **Application:** https://demo.easyappointments.org/
- **Test Type:** Manual functional and form-validation testing
- **Browser:** Google Chrome
- **Test Data:** Fictional values only
- **Execution Date:** 25 October 2026
- **Environment Note:** The public demo configuration and data may change or reset.

## 4. In Scope

- Service and provider selection
- Appointment date/time selection
- Default date/time behavior
- Required-field validation
- Invalid email and phone validation
- Confirmation summary verification
- Final booking confirmation

## 5. Out of Scope

- Source-code review
- Security penetration testing
- Load and performance testing
- Email delivery verification
- Database verification
- Cross-browser testing
- Administrative/provider-side configuration

## 6. Test Approach

Execute positive and negative manual test cases. Record actual results based on direct observation. Report defects only when a reproducible mismatch against an expected result is identified. Capture screenshots as supporting evidence where available.

## 7. Entry Criteria

- Public demo is accessible.
- Booking workflow is available.
- Fictional test data is prepared.

## 8. Exit Criteria

- Core booking workflow has been tested.
- Execution results are documented.
- Untested scenarios are marked **Not Run**.
- Partially verified scenarios are clearly identified.
- No unconfirmed defects are reported as confirmed.

## 9. Known Limitations

- The application is a public demo with generic sample service/provider names.
- Past dates were tested and confirmed to be disabled and non-clickable.
- Confirmation summary fields were compared with previous selections and entered details; all matched.
- Some additional scenarios remain untested or partially verified.
- No formal product requirements were provided by the application owner.

