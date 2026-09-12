# INC750760 – Cannot Print to Network Printer

**Priority:** Medium  
**Request Type:** Printer / Network Printing  
**User:** Tom Wilson (`twilson`)  
**Department:** Engineering  
**Location:** Floor 3  
**Printer:** Floor3-Printer-C  
**Date Completed:** September 13, 2026

## Summary
User was unable to print to the department network printer (Floor3-Printer-C). Print jobs were sent but nothing printed. The printer was powered on and had paper. The user needed documents printed before an afternoon meeting.

## Steps Taken
1. Claimed the ticket.
2. Reviewed the Print Server documentation and confirmed the correct IP address for Floor3-Printer-C (10.0.2.52).
3. Initiated a remote support session to the user’s workstation.
4. Opened Settings → Printers & Scanners and removed the existing (offline/incorrect) printer entry.
5. Re-added Floor3-Printer-C using the correct IP address.
6. Sent a test page — status showed Ready and “Test page sent”.
7. Confirmed printing was working.
8. Added resolution notes and closed the ticket.

## Resolution
The workstation had an outdated or incorrect printer configuration.  
After removing the old printer and re-adding it with the correct IP from the Print Server documentation, printing was restored successfully.

## Skills Demonstrated
- Use of internal documentation for network printer details
- Remote desktop support
- Printer removal and re-installation
- Network printer troubleshooting
- Test print verification

## Screenshots

![Print Server documentation](../images/017-cannot-print-network-printer-INC750760/print-server-docs.png)  
*Print Server documentation showing Floor3-Printer-C IP address 10.0.2.52*

![Printer ready and test sent](../images/017-cannot-print-network-printer-INC750760/printer-ready-test-sent.png)  
*Floor3-Printer-C showing Ready status and successful test page*
