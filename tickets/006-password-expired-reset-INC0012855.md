# INC0012855 – Password Expired / Unable to Log In

**Priority:** High  
**Request Type:** Account Access / Password Reset  
**User:** Maria Garcia (`mgarcia`)  
**Department:** Engineering  
**Location:** Floor 3  
**Date Completed:** August 11, 2026

## Summary
User returned from a 3-week vacation and was unable to log in. The system reported that her password had expired, but she could not change it from the login screen. As lead developer on the payment processing module with a Friday sprint deadline, this was a high-priority access issue.

## Steps Taken
1. Claimed the high-priority ticket and located the user account for Maria Garcia in Directory.
2. Reviewed the Authentication tab and confirmed the password was marked as expired.
3. Initiated identity verification by sending a one-time code to the user’s registered phone.
4. Received the verification code from the user via Team Chat and confirmed her identity.
5. Performed a password reset and generated a temporary password.
6. Securely shared the temporary password with the user so she could log in and set a new permanent password.
7. Added resolution notes and closed the ticket.

## Resolution
Password successfully reset after identity verification.  
Temporary password issued: `TempJ8br7r!`  
User was able to log in and regain access to her workstation and development environment.

## Skills Demonstrated
- Secure password reset process
- Identity verification before making account changes
- Handling expired password scenarios after extended absence
- Clear communication with the user during a time-sensitive outage
- High-priority account access support

## Screenshots

![Authentication status showing password expired](../images/006-password-expired-INC0012855/password-expired-status.png)  
*User account showing password expired status*

![Identity verification step](../images/006-password-expired-INC0012855/identity-verification.png)  
*Entering the verification code received from the user*

![Chat confirmation of verification code](../images/006-password-expired-INC0012855/user-chat-code.png)  
*User provided the one-time code via Team Chat*

![Temporary password issued](../images/006-password-expired-INC0012855/temp-password-issued.png)  
*Temporary password generated and ready to share securely*
