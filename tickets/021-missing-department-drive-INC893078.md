# INC893078 – Can’t Find Department Files (Drive Letter Missing)

**Priority:** Medium  
**Request Type:** Network Drive Mapping  
**User:** Tom Wilson (`twilson`)  
**Department:** Engineering  
**Location:** Floor 2  
**Date Completed:** September 21, 2026

## Summary
User reported that the department drive letter was missing from This PC. The drive had been working the previous week. Restarting the computer did not restore it. Internet connectivity was fine. This blocked access to critical department files needed for ongoing projects.

## Steps Taken
1. Claimed the ticket.
2. Contacted the user via chat and confirmed they needed the Engineering department shared drive.
3. Reviewed the File Server documentation and located the correct UNC path: `\\FILESERV01\departments\Engineering`.
4. Mapped the network drive using the documented path.
5. Confirmed the drive appeared and the user could access the department files.
6. Added resolution notes and closed the ticket.

## Resolution
The department drive mapping had been lost.  
After confirming the required share with the user and mapping `\\FILESERV01\departments\Engineering`, access was fully restored.

## Skills Demonstrated
- User communication to clarify requirements
- Use of internal documentation (File Server)
- Network drive mapping
- Remote / on-site file access support

## Screenshots
No screenshots were captured for this ticket.
