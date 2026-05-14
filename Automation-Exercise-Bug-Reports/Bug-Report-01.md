Bug Report TC015

Title: Whitespace in email field is not trimmed before login validation

Description:
On the login page, when a user enters their email address with leading or trailing spaces, the system fails to trim the whitespace before processing. This prevents a valid user from logging in, even with correct credentials.

Steps to Reproduce:
	1.	Open browser
	2.	Navigate to https://automationexercise.com
	3.	Click on “Signup / Login”
	4.	Enter email with leading/trailing spaces:  valid@gmail.com
	5.	Enter the correct password
	6.	Click the Login button
  
Expected Result:
The system should automatically trim whitespace from the email field and log the user in successfully.

Actual Result:
An error message is displayed and login fails, even though the credentials are valid.

Evidence:
https://jam.dev/c/c6abca62-9e30-4b10-8cc8-90b6260df5e6
