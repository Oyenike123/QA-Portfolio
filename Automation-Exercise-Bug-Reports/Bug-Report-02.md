Title: Weak password is accepted during signup with no validation

Description:
On the signup/account creation page, the system accepts extremely weak passwords (e.g. “123”) without any validation or warning. This poses a serious security risk to user accounts.

Steps to Reproduce:
	1.	Open browser
	2.	Navigate to https://automationexercise.com
	3.	Click on “Signup / Login”
	4.	Enter a valid name and new email, then click Signup
	5.	On the account creation form, enter a weak password: 123
	6.	Complete remaining fields and submit the form

Expected Result:
The system should reject the weak password and display a message requiring a stronger password (minimum 8 characters, including letters, numbers and symbols).

Actual Result:
The system accepts “123” as a valid password and creates the account with no error or warning shown.

Evidence:
https://jam.dev/c/c6abca62-9e30-4b10-8cc8-90b6260df5e6
