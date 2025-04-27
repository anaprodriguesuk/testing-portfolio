## Test Case Information
- TestCaseID: TC-PS5-Partner-001
- Tester: Ana Rodrigues
- Test Type: Functional
- Priority: High
- Environment: PlayStation 5, macOS Ventura 13.4.1 (Safari browser)
- Country: United Kingdom (UK)

## Pre-Conditions
- The app must be installed on the PlayStation 5.
- The user must have valid credentials from a supported partner service.
- Internet connection must be stable.

## Test Steps

| Step | Action |
|:----|:-------|
| 1 | Install the app on the PS5 through the PlayStation Store. |
| 2 | Open the app and check if the Sign In button is displayed. |
| 3 | Select the "Sign In via Partner" option. |
| 4 | Choose "On the Web" as the sign-in method. |
| 5 | Visit the website provided and enter the code shown on the TV screen. |
| 6 | Select a partner from the list. |
| 7 | Enter valid partner login details. |
| 8 | Check if the sign-in is successful on the TV screen. |

## Expected Result
- After entering the partner credentials, a success message should appear.
- The user should be automatically signed in on the PlayStation 5.

## Actual Result
- After entering valid partner credentials, an error message appeared:

  "Sorry, you don't have access within your subscription package. Contact your provider to add access."

- The user was not signed in successfully.

## Observations
- The issue may be related to the Partner account not having access rights.
