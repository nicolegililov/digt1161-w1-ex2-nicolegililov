# Bug Report: Submit Button Does Not Activate After Completing Login Form

## Bug ID
BUG-001

## Reported By
Nicole Gililov

## Date Reported
September 22, 2026

## Application / Page
Sample Application - Login Page

## Environment
- Device: Windows laptop
- Browser: Google Chrome
- Connection: Home Wi-Fi

## Description
The **Submit** button does not become active after entering information in all required login fields. This prevents the user from logging in.

## Steps to Reproduce
1. Open the Sample Application login page.
2. Enter a username in the **Username** field.
3. Enter a password in the **Password** field.
4. Select the **I agree to the terms** checkbox.
5. Try to select the **Submit** button.

## Expected Result
The Submit button should become active after the required fields are completed, allowing the user to log in.

## Actual Result
The Submit button remains disabled and cannot be selected, even after all required information is entered.

## Severity
High - users cannot log in to the application.

## Suggested Fix
Check the form-validation rules to ensure the Submit button activates when all required fields contain valid information.