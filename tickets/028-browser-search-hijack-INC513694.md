# INC513694 – Browser Search Hijacked (SearchWave)

**Priority:** Medium  
**Request Type:** Malware / Browser Hijacker Removal  
**User:** Jessica Tran (`jtran`)  
**Department:** Engineering  
**Location:** Floor 1  
**Date Completed:** October 17, 2026

## Summary
User reported that new browser tabs were opening to an unknown page called “SearchWave” instead of the normal search engine. Search results were filled with ads and appeared altered. The browser had also become noticeably slower over the previous few days. The user had not intentionally changed any settings.

## Steps Taken
1. Claimed the ticket and initiated a remote support session.
2. Ran a full security scan via Virus & threat protection.
3. Scan detected and removed 1 threat.
4. Identified the remaining cause as the browser extension “Free PDF Converter Pro”, which was redirecting searches.
5. Guided removal of the extension through Web Browser → Settings → Extensions (the scanner could not remove it automatically).
6. Confirmed that new tabs and search behaviour returned to normal and the browser was no longer slow.
7. Added resolution notes and closed the ticket.

## Resolution
The issue was caused by a combination of a detected threat and a malicious/unwanted browser extension (“Free PDF Converter Pro”) that was hijacking search redirects.  
After the security scan removed the threat and the extension was manually uninstalled, normal browser search and performance were restored.

## Skills Demonstrated
- Browser hijacker / adware identification
- Running and interpreting full security scans
- Manual removal of malicious browser extensions
- Restoring default browser search behaviour
- Addressing both security and performance impact
