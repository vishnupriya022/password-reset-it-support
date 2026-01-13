\# Password Reset – IT Support



\## Description

This project simulates a real-time IT support scenario where a user cannot log in due to a forgotten or expired password. It demonstrates the step-by-step troubleshooting process, resolution, and ticket closure.



\## Problem Statement

A user is unable to access their account due to:

\- Forgotten password

\- Expired password

\- Account locked after multiple failed login attempts



---



\## Step-by-Step Process



\### Step 1: Ticket Creation

\- The user reports a password reset issue.



\### Step 2: User Verification

\- Verify the user’s identity using username, email, or employee ID.  

\- This ensures you only reset the password for the correct user.  



\### Step 3: Check Account Status

\- On Windows:

&nbsp; - Open `Computer Management → Local Users and Groups → Users`

&nbsp; - Check if the account is locked or password expired

📸 Screenshot:  

!\[Account Status Check](screenshots/step3-account-status-check.png)



---



\### Step 4: Password Reset

\- Right-click the user → Set Password.

\- Enter a temporary password (e.g., Temp1234!)

\- Optional: Select User must change password at next logon

📸 Screenshot:  

!\[Password Reset](screenshots/step4-password-reset.png)



---



\### Step 5: Notify User

\- Share the temporary password securely (email or chat)  

\- Ask the user to log in and change their password immediately

📸 Screenshot:  

!\[User Notification](screenshots/step5-user-notification.png)



---



\### Step 6: Verify Login

\- Log in as the user with the temporary password  

\- Ensure the user can log in and change password successfully

📸 Screenshot:  

!\[Login Success](screenshots/step6-login-success.png)



---



\### Step 7: Close Ticket

\- Update ticket status to Resolved.

\- Password reset completed; user logged in successfully.





