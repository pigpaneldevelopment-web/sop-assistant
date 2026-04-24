# Overnight Room Status Discrepancy Resolution

**Property:** Ridgeline Lodge, Steamboat Springs, CO
**Department:** Night Audit
**Document Owner:** General Manager
**Version:** 1.0

## Purpose

Room status discrepancies — where OPERA Cloud's record of a room does not match its actual state — cause downstream problems: a guest arrives to find a room not ready, a Room Attendant cleans a room still occupied, a revenue posting attaches to the wrong reservation. Most discrepancies surface overnight when the audit runs and room statuses roll forward. This procedure defines how the Night Auditor at Ridgeline Lodge identifies, investigates, and resolves room status discrepancies before the morning shift inherits them.

## Scope

Applies to the Night Auditor. Covers the period from the start of overnight shift through the morning handover. Discrepancies identified by the daytime team follow the same investigative logic but are coordinated by the Director of Housekeeping rather than the Night Auditor.

## Responsibilities

- **Night Auditor:** Identifies discrepancies from the Arrivals, Departures, and Room Status reports; investigates; resolves where possible; documents for the morning team.
- **Manager on Duty:** Available by cell phone for unresolvable discrepancies that affect a guest overnight.
- **Director of Housekeeping:** Receives the discrepancy log at morning handover; resolves status issues that require physical room verification.
- **General Manager:** Reviews chronic discrepancy patterns as part of monthly operations review.

## What Creates a Discrepancy

Room status discrepancies arise from a handful of common sources.

### Check-Out Not Processed

A guest departed but the FDA did not process the check-out in OPERA Cloud. Room shows "Occupied" but the guest is gone.

### Stayover Assumed but Guest Departed Without Notice

Guest checked out early without stopping at the desk. Room shows "Occupied — Staying Over" but is actually "Vacant — Dirty."

### Late Check-Out Not Updated

FDA approved a late check-out but didn't update the Guest Card. Room shows "Vacant — Dirty" overnight but guest is still in-house.

### Housekeeping Status Not Synced

Room Attendant cleaned a room but didn't update status to "Clean" on the tablet. Room shows "Dirty" but is actually clean.

### Extended Stay Not Processed

Guest extended their stay at the desk but the FDA did not update the departure date. The audit's roll-forward marks the room as "Vacant" while the guest is still checked in.

### OOO Not Communicated to Front Office

A room flagged OOO by Housekeeping but the Front Office still assigned it to an incoming guest. Discrepancy surfaces when the guest arrives to a room they cannot enter or use.

## Detection Sequence

The Night Auditor detects discrepancies by cross-referencing three reports.

### The Departures Report (Midnight Check)

1. Pull the Departures Report from OPERA Cloud at midnight, filtered to today's departures.
2. Review any reservation marked "Expected Departure" that is still showing as "Occupied."
3. For each, check the In-House Guest list. Is the guest confirmed as staying another night? If not, this is a probable early departure.
4. Physically check the room (see Room Verification below) to confirm.

### The Arrivals Report (1:00 AM Check)

1. Pull the Arrivals Report, filtered to today's arrivals.
2. Review any reservation marked "Pending Arrival" against the In-House Guest list. Any arrival that has somehow been checked in twice (a double-check-in error) is identified here.
3. Identify any pre-assigned room that now shows a status other than "Clean and Inspected" — these are rooms that should be ready but aren't, indicating a reassignment is needed.

### The Room Status Report (2:00 AM Check)

1. Pull the full Room Status Report.
2. Scan for any room showing an unusual status combination:
   - "Occupied" with no in-house guest
   - "Vacant — Dirty" assigned to an in-house reservation
   - "Out of Order" that is in use
   - Any room with "Last Departure" date more than 24 hours ago still showing "Occupied"
3. Every oddity is a discrepancy candidate. Investigate.

## Investigation Sequence

For each suspected discrepancy, work through the following before escalating.

### Step 1 — Review the Guest Card

1. Pull the reservation in question.
2. Review all Guest Card notes for any late check-out approval, extension, or stay modification.
3. Review the folio for recent postings that might indicate whether the guest is still in-house (minibar post at 10:00 PM suggests occupied; none since yesterday morning suggests departed).

### Step 2 — Review Shift Notes

1. Open the Shift Handover Pass-On Log for the evening shift.
2. Search for mentions of the room number or guest name.
3. Evening FDAs often note approved changes that didn't make it into the system.

### Step 3 — Check Physical Indicators

1. Review key programming logs in the electronic lock system. Has the room's key been used in the last 24 hours? If no recent key use, the room is likely vacant.
2. Check Housekeeping's dispatch log for any room condition notes from the day shift.
3. For rooms that show "Occupied" but have no recent key activity, proceed to Room Verification.

### Step 4 — Room Verification

Physical verification is a last resort. Done only when electronic checks don't resolve the discrepancy and the resolution can't wait until morning.

1. Call the room phone. Let it ring 6 times. A guest present and answering resolves the question.
2. If no answer, consider whether the guest might be asleep. If resolving the discrepancy doesn't need to happen overnight, defer to morning.
3. If resolution is needed overnight (e.g., an incoming late arrival needs the room), the Night Auditor may knock on the door:
   - Knock softly three times.
   - Wait 30 seconds.
   - Knock again and announce "Hotel management checking on your room."
   - If no answer after a third knock, enter with the master key. Prop the door open. Do not close the door behind you.
   - Verify whether the room is occupied (luggage present, belongings in the room) or vacated.
4. Document the verification — date, time, reason, outcome — in the Shift Notes. Entering a guest room overnight is a serious step and needs a clean record.

## Resolution Sequence

Once a discrepancy is confirmed, resolve in OPERA Cloud.

### Check-Out Not Processed

1. Verify the guest has indeed departed.
2. Process the check-out retroactively in OPERA Cloud, dated to the departure day.
3. Post any outstanding folio charges per standard close procedure.
4. If the guest cannot be reached for folio dispute, flag to the GM for morning follow-up.

### Stayover Became Early Departure

1. Process the check-out.
2. Retain any charges for unused nights per the property's early departure policy (check the reservation notes for any pre-approved early departure terms).
3. Document the early departure and charge decision in the Guest Card.

### Late Check-Out Not Logged

1. Update the Guest Card with the approved late check-out time.
2. Extend the reservation departure timestamp in OPERA Cloud.
3. Communicate to Housekeeping via morning notes so the room is not cleaned early.

### Housekeeping Status Not Synced

1. Confirm with the Director of Housekeeping's dispatch log that the room was actually cleaned.
2. Update status to "Clean and Inspected" in OPERA Cloud if confirmed.
3. If unconfirmed, leave the status as-is and flag for morning inspection.

### Extended Stay Not Processed

1. Verify with the guest (call the room if needed) that they are extending.
2. Extend the reservation in OPERA Cloud.
3. Post the additional night's charges.
4. Verify the rate for the extended night — extended-stay rates may differ from the original rate.

### OOO vs. Assigned

1. Reassign the incoming arrival to an alternate room of the same type or better.
2. Notify the Front Desk for the next shift.
3. Leave a note for the arriving guest if they have already arrived and been temporarily accommodated in the lobby.

## Unresolvable Discrepancies

Some discrepancies cannot be closed overnight. For these, document fully and hand off.

1. Log the discrepancy in the Shift Notes Pass-On Log with all investigation steps taken.
2. Flag for the morning Manager on Duty as a priority item.
3. If the discrepancy affects an incoming arrival or an in-house guest's experience, escalate to the MOD by cell phone before the situation reaches the guest.

## Common Failure Modes

- Assuming a discrepancy is a non-issue because "the system must be wrong" — every discrepancy has a cause; find it.
- Entering a guest room overnight without clear justification and documentation — this is a serious boundary.
- Processing a retroactive check-out without reviewing the folio — leaves legitimate charges unposted.
- Deferring all discrepancies to morning — small ones, sure; affected-guest ones, no.

## Documentation

- **Shift Notes Pass-On Log** — primary record for any discrepancy investigated.
- **Guest Card notes** — reservation-level documentation for any resolved discrepancy.
- **Folio posting log** — for retroactive check-outs and extensions.
- **Room Entry Log** — any physical room entry overnight is documented with date, time, reason, outcome, and Night Auditor initial.

## Escalation Triggers

Contact the Manager on Duty by cell phone if:
- A room entered overnight shows evidence of a medical emergency or security issue
- A discrepancy affects an incoming late arrival that needs immediate resolution
- A guest charge dispute arises from a retroactive posting
- The discrepancy cannot be attributed to any apparent cause (indicates possible system or data integrity issue)

## Related Documents

- Automated Night Audit Monitoring and Exception Handling SOP
- After-Hours Check-In Procedure SOP
- Shift Handover and Pass-On Log SOP
- Out-of-Order Room Reporting and Tracking SOP
- Departure and Check-Out Procedure SOP

## Revision History

| Date | Version | Change Summary | Revised By |
|---|---|---|---|
| [Initial Date] | 1.0 | Initial publication | General Manager |
