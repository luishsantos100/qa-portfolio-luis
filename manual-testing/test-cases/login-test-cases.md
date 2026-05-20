# Manual Test Cases - Login Functionality

## Project Area

Login / Authentication

## Objective

Validate that users can log in successfully with valid credentials and that the system handles invalid login attempts correctly.

## Test Environment

- Application: SauceDemo
- Environment: QA / Demo
- Browser: Chrome
- Device: Desktop
- Tester: Luis Henrique dos Santos
- Date: 2026-05-20

---

## Test Case Summary

| Test Case ID | Scenario | Priority | Status |
|---|---|---|---|
| TC-LOGIN-001 | Successful login with valid credentials | High | Ready for Execution |
| TC-LOGIN-002 | Login with invalid password | High | Ready for Execution |
| TC-LOGIN-003 | Login with empty username and password | Medium | Ready for Execution |
| TC-LOGIN-004 | Login with empty password | Medium | Ready for Execution |
| TC-LOGIN-005 | Logout after successful login | Medium | Ready for Execution |

---

## Test Case ID: TC-LOGIN-001

### Title

Successful login with valid credentials

### Preconditions

- The user has a valid account.
- The user is on the login page.

### Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | Open the login page | The login page should be displayed |
| 2 | Enter a valid username | The username should be accepted |
| 3 | Enter a valid password | The password should be accepted |
| 4 | Click the Login button | The user should be redirected to the home page |

### Expected Result

The user should be successfully authenticated and redirected to the home page.

### Actual Result

The user was successfully authenticated and redirected to the SauceDemo inventory page after entering valid credentials.

### Status

Passed

### Evidence

- Screenshot: https://jam.dev/c/3755a9de-b048-44cb-9c21-ff65929bb819 https://jam.dev/c/f236ce4e-40e8-4337-91cb-649ae1bddd16
- Video: https://jam.dev/c/30027615-21a5-4dd9-9999-8a499bcc976d
- Notes: No issues were found during this test execution.

---

## Test Case ID: TC-LOGIN-002

### Title

Login with invalid password

### Preconditions

- The user has a valid username.
- The user is on the login page.

### Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | Open the login page | The login page should be displayed |
| 2 | Enter a valid username | The username should be accepted |
| 3 | Enter an invalid password | The password field should accept the input |
| 4 | Click the Login button | An error message should be displayed |

### Expected Result

The system should not authenticate the user and should display an appropriate error message.

### Actual Result

To be completed during test execution.

### Status

Ready for Execution

### Evidence

- Screenshot: https://jam.dev/c/c7146f3e-1170-4aab-8e2f-bb7c43f1178d
- Video: https://jam.dev/c/a633d387-af36-4de8-975f-df6597da6cb9
- Notes: No issues were found during this test execution.

---

## Test Case ID: TC-LOGIN-003

### Title

Login with empty username and password

### Preconditions

- The user is on the login page.

### Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | Open the login page | The login page should be displayed |
| 2 | Leave the username field empty | The field should remain empty |
| 3 | Leave the password field empty | The field should remain empty |
| 4 | Click the Login button | A validation message should be displayed |

### Expected Result

The system should prevent login and display a validation message for required fields.

### Actual Result

To be completed during test execution.

### Status

Ready for Execution

### Evidence

- Screenshot: To be added
- Video: To be added
- Notes: To be added

---

## Test Case ID: TC-LOGIN-004

### Title

Login with empty password

### Preconditions

- The user is on the login page.

### Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | Open the login page | The login page should be displayed |
| 2 | Enter a valid username | The username should be accepted |
| 3 | Leave the password field empty | The password field should remain empty |
| 4 | Click the Login button | A validation message should be displayed |

### Expected Result

The system should prevent login and display a validation message indicating that the password is required.

### Actual Result

To be completed during test execution.

### Status

Ready for Execution

### Evidence

- Screenshot: To be added
- Video: To be added
- Notes: To be added

---

## Test Case ID: TC-LOGIN-005

### Title

Logout after successful login

### Preconditions

- The user is successfully logged in.

### Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | Log in with valid credentials | The user should be redirected to the home page |
| 2 | Click the menu or account option | The logout option should be displayed |
| 3 | Click Logout | The user should be logged out |
| 4 | Try to access the home page again | The system should redirect the user to the login page |

### Expected Result

The user should be successfully logged out and should not be able to access authenticated pages without logging in again.

### Actual Result

To be completed during test execution.

### Status

Ready for Execution

### Evidence

- Screenshot: To be added
- Video: To be added
- Notes: To be added

---

## Overall Result

Ready for Execution

## Defects Found

None at this stage.

## Conclusion

These test cases cover basic login functionality, including successful authentication, invalid credentials, required field validation, and logout behavior.