# INC257781 – Printer Says Offline and Will Not Print

**Priority:** High  
**Request Type:** Printer / Network Printing  
**User:** Michael Brown (`mbrown`)  
**Department:** Engineering  
**Location:** Floor 1  
**Printer:** Floor1-Printer-A  
**Date Completed:** October 17, 2026

## Summary
User reported that Floor1-Printer-A was showing as offline. Restarting the computer did not resolve the issue. The problem began after weekend maintenance. The user needed to print important reports for a Monday morning meeting.

## Steps Taken
1. Claimed the high-priority ticket.
2. Reviewed the Print Server documentation and confirmed the correct IP address for Floor1-Printer-A (10.0.2.50).
3. Remote accessed the user’s workstation.
4. Removed the existing offline printer entry.
5. Re-added Floor1-Printer-A using the correct IP address from documentation.
6. Sent a test page — print job completed successfully.
7. Confirmed the printer status showed Ready.
8. Added resolution notes and closed the ticket.

## Resolution
The printer connection on the workstation was incorrect or stale following weekend maintenance.  
Re-adding the printer with the documented IP address (10.0.2.50) restored normal printing.

## Skills Demonstrated
- Use of internal Print Server documentation
- Network printer troubleshooting
- Removing and re-adding network printers
- Test print verification
- Restoring printing capability under time pressure
