\# Manual Test Cases - Login Functionality



\## Project Area



Login / Authentication



\## Objective



Validate that users can log in successfully with valid credentials and that the system handles invalid login attempts correctly.



\## Test Environment



\- Application: Demo E-commerce Website

\- Environment: QA / Demo

\- Browser: Chrome

\- Device: Desktop

\- Tester: Luis Henrique Santos

\- Date: YYYY-MM-DD



\---



\## Test Case Summary



| Test Case ID | Scenario | Priority | Status |

|---|---|---|---|

| TC-LOGIN-001 | Successful login with valid credentials | High | Not Executed |

| TC-LOGIN-002 | Login with invalid password | High | Not Executed |

| TC-LOGIN-003 | Login with empty username and password | Medium | Not Executed |

| TC-LOGIN-004 | Login with empty password | Medium | Not Executed |

| TC-LOGIN-005 | Logout after successful login | Medium | Not Executed |



\---



\## Test Case ID: TC-LOGIN-001



\### Title



Successful login with valid credentials



\### Preconditions



\- The user has a valid account.

\- The user is on the login page.



\### Test Steps



| Step | Action | Expected Result |

|---|---|---|

| 1 | Open the login page | The login page should be displayed |

| 2 | Enter a valid username | The username should be accepted |

| 3 | Enter a valid password | The password should be accepted |

| 4 | Click the Login button | The user should be redirected to the home page |



\### Expected Result



The user should be successfully authenticated and redirected to the home page.



\### Actual Result



To be completed during test execution.



\### Status



Not Executed



\### Evidence



\- Screenshot: To be added

\- Video: To be added

\- Notes: To be added



\---



\## Test Case ID: TC-LOGIN-002



\### Title



Login with invalid password



\### Preconditions



\- The user has a valid username.

\- The user is on the login page.



\### Test Steps



| Step | Action | Expected Result |

|---|---|---|

| 1 | Open the login page | The login page should be displayed |

| 2 | Enter a valid username | The username should be accepted |

| 3 | Enter an invalid password | The password field should accept the input |

| 4 | Click the Login button | An error message should be displayed |



\### Expected Result



The system should not authenticate the user and should display an appropriate error message.



\### Actual Result



To be completed during test execution.



\### Status



Not Executed



\### Evidence



\- Screenshot: To be added

\- Video: To be added

\- Notes: To be added



\---



\## Test Case ID: TC-LOGIN-003



\### Title



Login with empty username and password



\### Preconditions



\- The user is on the login page.



\### Test Steps



| Step | Action | Expected Result |

|---|---|---|

| 1 | Open the login page | The login page should be displayed |

| 2 | Leave the username field empty | The field should remain empty |

| 3 | Leave the password field empty | The field should remain empty |

| 4 | Click the Login button | A validation message should be displayed |



\### Expected Result



The system should prevent login and display a validation message for required fields.



\### Actual Result



To be completed during test execution.



\### Status



Not Executed



\### Evidence



\- Screenshot: To be added

\- Video: To be added

\- Notes: To be added



\---



\## Test Case ID: TC-LOGIN-004



\### Title



Login with empty password



\### Preconditions



\- The user is on the login page.



\### Test Steps



| Step | Action | Expected Result |

|---|---|---|

| 1 | Open the login page | The login page should be displayed |

| 2 | Enter a valid username | The username should be accepted |

| 3 | Leave the password field empty | The password field should remain empty |

| 4 | Click the Login button | A validation message should be displayed |



\### Expected Result



The system should prevent login and display a validation message indicating that the password is required.



\### Actual Result



To be completed during test execution.



\### Status



Not Executed



\### Evidence



\- Screenshot: To be added

\- Video: To be added

\- Notes: To be added



\---



\## Test Case ID: TC-LOGIN-005



\### Title



Logout after successful login



\### Preconditions



\- The user is successfully logged in.



\### Test Steps



| Step | Action | Expected Result |

|---|---|---|

| 1 | Log in with valid credentials | The user should be redirected to the home page |

| 2 | Click the menu or account option | The logout option should be displayed |

| 3 | Click Logout | The user should be logged out |

| 4 | Try to access the home page again | The system should redirect the user to the login page |



\### Expected Result



The user should be successfully logged out and should not be able to access authenticated pages without logging in again.



\### Actual Result



To be completed during test execution.



\### Status



Not Executed



\### Evidence



\- Screenshot: To be added

\- Video: To be added

\- Notes: To be added



\---



\## Overall Result



Not Executed



\## Defects Found



None at this stage.



\## Conclusion



These test cases cover basic login functionality, including successful authentication, invalid credentials, required field validation, and logout behavior.

