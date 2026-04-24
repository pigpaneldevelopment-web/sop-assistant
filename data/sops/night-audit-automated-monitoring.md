# Automated Night Audit Monitoring and Exception Handling

**Property:** The Cannon & Vine, Nashville, TN
**Department:** Night Audit
**Document Owner:** General Manager
**Version:** 1.0

## Purpose

The night audit at The Cannon & Vine runs automatically in Cloudbeds. The Night Auditor's role is not to run a traditional manual audit — it is to monitor the automated run, handle exceptions, serve overnight guests, and ensure the property is operationally ready for the incoming morning shift. This procedure defines what the Night Auditor does around the automated audit and how to handle the things the system cannot resolve alone.

## Scope

Applies to the Night Auditor on shift overnight (typically 11:00 PM to 7:00 AM). Covers automated audit monitoring, exception handling, overnight guest service, and morning handover. Covers the weeknight solo-staffed overnight. On busy weekend overnights when a second staff member is scheduled, responsibilities are shared but sign-off remains with the Night Auditor.

## Responsibilities

- **Night Auditor:** Monitors the automated audit run; resolves exceptions; handles overnight guest service; prepares and delivers morning handover.
- **Manager on Duty:** Available by cell phone for any exception the Night Auditor cannot resolve. Unavoidably contacted on any 911 incident or security event.
- **General Manager:** Reviews exception log and any escalations as part of the morning operations check-in.

## What the Automated Audit Does

The Cloudbeds end-of-day process runs automatically at 3:00 AM and handles the following without intervention:

- Closes the financial day, rolling all postings to the next business day.
- Posts no-show charges per property policy for any reservations marked as no-show.
- Rolls pending room and tax postings.
- Generates the Daily Revenue Report, Arrivals Report, Departures Report, and Room Revenue by Segment report.
- Updates forecast occupancy for the incoming day.

The Night Auditor does not manually run any of this. The system runs it. The Night Auditor's job is to verify it ran cleanly and to handle what the system flagged.

## Pre-Audit Monitoring (11:00 PM – 3:00 AM)

The Night Auditor prepares the environment for a clean audit run.

### 11:00 PM Checklist

1. Take handover from the evening Front Desk Agent per the Shift Handover SOP.
2. Log into Cloudbeds. Open the End-of-Day Status screen.
3. Review any reservations flagged as "Pending Arrival." Any guest expected but not arrived is followed up per the No-Show Processing SOP.
4. Review any open folios with unusual charges or credits. Flag anything that looks like a posting error for review before the audit runs.
5. Verify all house accounts (group masters, airline crew contracts) have been posted for the day.

### 1:00 AM Checklist

1. Walk the property. Confirm all public doors are secured, the restaurant and bar are closed per F&B closing SOP, and no guest issues are in progress.
2. Return to the desk. Confirm the Cloudbeds audit is scheduled for 3:00 AM on the End-of-Day Status screen.
3. Mark any reservations that guests have not yet arrived for as "Pending Late Arrival" with a note in the Guest Card. This prevents the system from auto-flagging them as no-shows if they arrive at 2:30 AM.

## Audit Run Monitoring (3:00 AM – 3:30 AM)

The Night Auditor monitors the automated audit in real time.

1. At 3:00 AM, the End-of-Day Status screen will show "In Progress."
2. Do not interrupt. Do not log out. Do not close the browser.
3. If a guest arrives during the audit window, check them in via the standard procedure — the system queues the check-in and posts it to the new business day once the audit completes.
4. The audit typically completes in 8 to 15 minutes. A run exceeding 30 minutes is an exception.
5. When the audit completes, the End-of-Day Status screen will show "Complete" with a timestamp.

## Post-Audit Verification (3:30 AM – 4:00 AM)

After the audit completes, the Night Auditor verifies the run.

1. Open the Daily Revenue Report. Confirm the date is the correct business day.
2. Confirm room revenue, F&B revenue, and other revenue reconcile to the evening's POS totals. A variance greater than $50 is flagged for the General Manager.
3. Confirm all no-shows were posted with the correct charge.
4. Confirm the Arrivals Report for the new business day is populated.
5. Confirm the Housekeeping status rolled — rooms that were "Occupied — Departing" yesterday now show "Vacant — Dirty."
6. Export the Daily Revenue Report as PDF to the shared drive. File by date.
7. Complete the Night Audit Sign-Off Log entry in Cloudbeds Shift Notes.

## Exception Handling

Exceptions are what the Night Auditor actually gets paid to handle. The most common categories:

### Audit Fails to Start at 3:00 AM

1. Verify no Cloudbeds maintenance is scheduled (check Cloudbeds status page).
2. Confirm no open folios are in an error state.
3. Wait until 3:30 AM. If the audit still has not started, contact the Manager on Duty by cell.
4. Do not force an audit run without GM authorization.

### Audit Fails Mid-Run

1. Do not refresh or re-initiate.
2. Screenshot the error message.
3. Contact Cloudbeds support at the 24/7 number posted at the desk.
4. Notify the Manager on Duty by cell within 10 minutes.

### Revenue Does Not Reconcile

1. Identify the variance category (room, F&B, other).
2. Pull the POS closing reports from MICROS and compare line by line to the Cloudbeds revenue report.
3. For F&B variance over $50, contact the F&B Supervisor's on-call phone.
4. Document the variance in the Shift Notes and hand off to the morning Manager with the supporting POS reports.

### Guest Arrives During the Audit Window

Proceed with standard check-in. The system queues the posting and applies it to the new business day automatically.

### Room Status Discrepancy After Audit

If a room shows as "Vacant — Dirty" but was supposed to remain occupied (multi-night stay), see the Overnight Room Status Discrepancy Resolution SOP.

## Overnight Guest Service

Audit duties do not override guest service. Standard expectations:

- Answer the front desk phone within 3 rings.
- Greet any lobby guest within 10 seconds.
- Handle after-hours check-ins per the Arrival and Check-In Procedure SOP (After-Hours Arrivals section).
- Handle any noise complaint, lockout, or maintenance issue per the Overnight Guest Request SOP.
- Do not leave the front desk unattended. If the property must be walked (e.g., noise complaint), lock the desk and post a "Back in 5 minutes" sign with a phone number that reaches you.

## Morning Handover (6:45 AM – 7:00 AM)

1. Finalize the Shift Notes Pass-On Log per the Shift Handover SOP.
2. Confirm the morning FDA has the Daily Revenue Report, Arrivals Report, and any exception notes ready at the desk.
3. Verbally walk through any exception handled overnight — even resolved ones.
4. Stay until handover is complete even if it runs past scheduled end.

## Escalation Triggers

Contact the Manager on Duty immediately if:
- The audit fails to complete by 4:00 AM
- Revenue variance exceeds $50 and cannot be traced
- Any security or medical incident occurs
- A guest is uncooperative and the Night Auditor is unable to de-escalate
- The property's internet or power is out

## Documentation

- **Night Audit Sign-Off Log:** Daily entry in Cloudbeds Shift Notes.
- **Exception Log:** Free-text notes in the Pass-On Log, with screenshots attached where relevant.
- **Daily Revenue Report:** Archived daily PDF in the shared drive.

## Related Documents

- No-Show Processing and Charge Policy SOP
- Overnight Room Status Discrepancy Resolution SOP
- Shift Handover and Pass-On Log SOP
- After-Hours Check-In Procedure SOP

## Revision History

| Date | Version | Change Summary | Revised By |
|---|---|---|---|
| [Initial Date] | 1.0 | Initial publication | General Manager |
