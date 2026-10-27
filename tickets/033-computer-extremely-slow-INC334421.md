# INC334421 – Computer Extremely Slow (Suspected Virus)

**Priority:** Medium  
**Request Type:** Performance / Troubleshooting  
**User:** Nina Patel (`npatel`)  
**Department:** Engineering  
**Location:** Floor 2  
**Date Completed:** October 27, 2026

## Summary
User reported that her computer had become extremely slow since the morning. Applications took a long time to open and the system felt like it was constantly working. She suspected a virus (a colleague had experienced something similar). A restart only helped temporarily.

## Steps Taken
1. Claimed the ticket and initiated a remote support session.
2. Ran a full virus / threat scan – results were clean.
3. Installed all pending Windows and driver updates.
4. Cleaned up disk space.
5. Opened Task Manager and reviewed processes and startup items – no suspicious high-CPU processes or unknown startup programs.
6. Identified that the Cloud Drive sync engine was continuously hammering disk and network with no progress (stuck sync).
7. Opened Cloud Drive in File Explorer and forced a resync.
8. Confirmed the system was no longer resource-constrained and performance returned to normal.
9. Added resolution notes and closed the ticket.

## Resolution
The slowdown was not caused by malware.  
Root cause was a stuck Cloud Drive synchronisation process consuming disk and network resources. Forcing a resync, combined with installing updates and freeing disk space, restored normal performance.

## Skills Demonstrated
- Performance troubleshooting (Task Manager analysis)
- Differentiating malware symptoms from other resource issues
- Full security scanning
- Disk cleanup and update management
- Diagnosing and resolving stuck cloud sync processes
