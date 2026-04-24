# End-of-Day Revenue Report Review and Filing

**Property:** Salinas Point Inn, Central California Coast
**Department:** Night Audit
**Document Owner:** General Manager
**Version:** 1.0

## Purpose

The End-of-Day Revenue Report is the single most important financial artifact the property produces each day. It reconciles room revenue, F&B revenue, other revenue, and payment types against the PMS's closed books — and it is the document the GM, Accounting, and ownership rely on to understand daily performance. This procedure defines how the Night Auditor reviews the report after the automated audit completes, how variances are investigated, and how the report is filed.

## Scope

Applies to the Night Auditor on shift during the 3:00 AM audit window. Covers the review sequence between audit completion and shift end at 7:00 AM. Does not cover monthly or year-to-date reconciliation — those are Accounting functions.

## Responsibilities

- **Night Auditor:** Reviews the report immediately after audit completion; investigates any variance; files the report; flags items for the morning GM review.
- **General Manager:** Reviews the filed report each morning as part of the operations check-in; resolves any flagged variance.
- **F&B Supervisor:** Available by cell phone for F&B variance investigation if needed during the overnight.
- **Accounting:** Uses the daily report as the source for monthly reconciliation.

## Timing

Report review begins immediately after the Mews night audit completes (typically 3:10–3:20 AM) and completes within 30 minutes. The review is separate from and follows the audit monitoring sequence defined in the Automated Night Audit Monitoring SOP.

## The Report's Components

The Mews End-of-Day Revenue Report contains:

1. **Room Revenue Summary** — by segment (transient, group, negotiated), by room type, by rate category.
2. **Room Tax Summary** — state tax, local tax, resort or tourism fees.
3. **F&B Revenue Summary** — by outlet (restaurant, bar, in-room dining), by revenue sub-category (food, beverage, non-alcoholic).
4. **Other Revenue Summary** — spa, parking, laundry, minor revenue lines.
5. **Payment Type Summary** — cash, credit card (by network), direct bill, gift certificate, comp.
6. **Adjustments Summary** — discounts applied, comps posted, service recovery credits.
7. **Occupancy Statistics** — rooms sold, rooms available, ADR, RevPAR, occupancy percentage.
8. **Group Activity** — nights sold per group, per group revenue.

## Step 1 — Initial Scan

Upon the report generating, perform a 5-minute initial scan.

1. Verify the report date is correct. A report dated to the wrong day (rare but possible if the audit date rolled incorrectly) requires immediate escalation to Mews support.
2. Verify all expected sections populated. An empty or zero F&B section on a day the restaurant was open is a flag.
3. Verify occupancy statistics match your knowledge of the day. 85% occupancy on a report for a day that had 20 rooms showing in the Arrivals Report is a flag.

## Step 2 — Room Revenue Reconciliation

Room revenue is the largest component and the most reliable.

1. Compare the Room Revenue Summary total to expected revenue based on the day's rooms sold and the average rate sold.
2. Material variance (more than 5% from expected) is investigated:
   - Was there a group departure with a contracted rate not reflected correctly?
   - Was there a last-minute package booking with a bundled rate?
   - Was there a comp room that posted as rate-zero?
3. Verify room tax totals calculate correctly against room revenue. Tax is automated but occasionally fails on custom rate codes.
4. For any group, verify that group nights sold in the Group Activity section matches the expected pickup per the Group Master.

## Step 3 — F&B Revenue Reconciliation

F&B revenue is the section most prone to variance.

1. Compare the F&B Revenue Summary to the F&B shift-end totals from Toast (if Toast was the property's POS).
2. At Salinas Point Inn the POS is integrated with Mews, so totals should match automatically. They do not always.
3. Material variance (more than $50) is investigated:
   - Is there a posting delay — a late close ticket that didn't make the 3:00 AM cutoff?
   - Is there a manual F&B adjustment that was entered directly into Mews and not through the POS?
   - Is there a group catering event that was billed through Mews rather than through Toast?
4. If the variance cannot be resolved with the tools available overnight, flag to the F&B Supervisor via email and to the GM in the morning handover.

## Step 4 — Other Revenue Reconciliation

Spa, parking, and other revenue lines are typically small but worth reviewing.

1. Compare spa revenue to the Spa Daily Report.
2. Compare parking revenue to the parking log.
3. Any variance is flagged but generally reviewed in the morning rather than escalated overnight.

## Step 5 — Payment Type Reconciliation

The Payment Type Summary must balance against the shift-end totals.

1. Cash totals match the sum of F&B cash deposits, Front Desk cash deposits, and any other cash received.
2. Credit card totals match the Mews credit card batch. Mismatch here is serious — it indicates a settlement issue that Accounting will have to resolve.
3. Direct bill totals post to the appropriate direct bill accounts for Accounting follow-up.
4. Comp totals match the comp approvals logged by the Manager on Duty.

## Step 6 — Comp and Adjustment Review

Every comp or adjustment must have an authorization trail.

1. Review each comp posted during the day.
2. For any comp exceeding $50, verify a Manager or GM authorization is logged.
3. Review each adjustment (rate reduction, removed charge).
4. For any adjustment exceeding $50, verify authorization.
5. Any unauthorized comp or adjustment is flagged to the GM.

## Step 7 — Occupancy Statistics Verification

1. Confirm rooms sold matches the Arrivals + In-House count after check-out processing.
2. Confirm ADR calculates correctly: Room Revenue / Rooms Sold.
3. Confirm RevPAR calculates correctly: Room Revenue / Rooms Available.
4. These are automated but occasional rounding or rate-code issues can produce odd numbers. Flag anything that doesn't look right.

## Step 8 — Variance Notes

For every variance identified above, create a note in the End-of-Day Variance Log.

Each entry contains:

- Date
- Section (Room Revenue, F&B, Payment Type, etc.)
- Variance amount
- Suspected cause
- Action taken (resolved overnight / flagged for morning review)
- Night Auditor initial

This log is the handover to the GM in the morning.

## Step 9 — Filing

Once the review is complete:

1. Export the End-of-Day Revenue Report as PDF.
2. Save to the shared drive under `/Revenue Reports/YYYY/MM/YYYY-MM-DD_EOD_Report.pdf`. Use the same naming convention every night.
3. Email the PDF to: General Manager, Controller, and Accounting inbox. Single email at the end of review.
4. Attach the Variance Log notes to the email body — copy-paste from the log, not a separate attachment.
5. Record in the Audit Sign-Off Log that the report has been reviewed and filed.

## Step 10 — Morning Handover

During the 7:00 AM shift handover:

1. Verbally walk the morning FDA or Manager through any flagged variance.
2. Confirm the FDA has access to the filed report in case the GM asks questions before reviewing email.
3. Ensure the Variance Log is visible and ready for the morning operations meeting.

## Common Variance Categories

Over time, patterns emerge. The Night Auditor documents recurring categories:

- **OTA commission timing** — commission sometimes posts the day after the stay, creating a temporary variance between gross and net room revenue.
- **Group master settlement** — contracted charges post to master folio on different cadences than individual room revenue.
- **Comp posting delay** — a complimentary meal approved by the F&B Supervisor may not post to Mews until the next day if the POS close missed the audit window.
- **Gift certificate redemption** — depending on configuration, gift certificate redemptions post against current revenue or against a liability account; understanding which is the configuration at the property is essential.

## Common Failure Modes

- Skipping variance review on a "quiet night" because revenue looks about right — the $200 discrepancy that goes unflagged today compounds into a month-end puzzle.
- Emailing the report to the GM without the Variance Log notes — leaves the GM to discover issues cold.
- Filing the PDF under an inconsistent naming convention — makes year-end reconciliation painful.

## Escalation Triggers

Contact the Manager on Duty (and the GM by email) if:
- Credit card batch does not reconcile to Mews credit totals
- Any variance exceeds $500 and cannot be resolved overnight
- Unauthorized comp or adjustment exceeding $100 is identified
- The report fails to generate at all

## Documentation

- **End-of-Day Revenue Report PDF** — filed per convention above.
- **Variance Log** — shared document in the Accounting folder.
- **Audit Sign-Off Log** — Mews Shift Notes entry.
- **Morning email to GM, Controller, Accounting** — daily send.

## Related Documents

- Automated Night Audit Monitoring and Exception Handling SOP
- End-of-Shift Cash Reconciliation (F&B) SOP
- No-Show Processing and Charge Policy SOP
- Group Billing and Master Folio Management SOP

## Revision History

| Date | Version | Change Summary | Revised By |
|---|---|---|---|
| [Initial Date] | 1.0 | Initial publication | General Manager |
