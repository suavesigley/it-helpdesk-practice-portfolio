# INC674125 – Entire Floor 1 Has No Internet After Power Outage

**Priority:** Critical  
**Request Type:** Network / Infrastructure  
**Reported by:** Priya Sharma (`psharma`)  
**Department:** Engineering  
**Location:** Floor 1  
**Date Completed:** October 8, 2026

## Summary
After a brief power flicker, all users on Floor 1 lost both wired and wireless internet connectivity. Users on other floors remained unaffected. Approximately 30 users were unable to access any network resources, halting work on the floor.

## Steps Taken
1. Claimed the Critical ticket.
2. Opened Tools → Server Room → Devices.
3. Identified that the Floor 1 Switch was in ERROR state while all other switches and the Metro ISP were online.
4. Rebooted the Floor 1 Switch.
5. Confirmed the switch returned to ONLINE status.
6. Verified that Floor 1 connectivity was restored.
7. Added resolution notes and closed the ticket.

## Resolution
The Floor 1 Switch failed to recover properly after the power flicker and remained in an ERROR state.  
A reboot of the switch restored full network connectivity to Floor 1.

## Skills Demonstrated
- Critical network outage response
- Server Room device monitoring and diagnosis
- Identifying floor-specific switch failure after power event
- Network device reboot and verification

## Screenshots

![Floor 1 Switch in ERROR – Overview](../images/026-floor1-outage-INC674125/floor1-switch-error-overview.png)  
*Server Room Overview showing Floor 1 Switch in ERROR state*

![Floor 1 Switch in ERROR – Devices](../images/026-floor1-outage-INC674125/floor1-switch-error-devices.png)  
*Devices tab confirming Floor 1 Switch ERROR while other devices are online*
