# Group Billing and Master Folio Management

**Property:** The Ironwood, Sedona, AZ
**Department:** Group Management
**Document Owner:** General Manager
**Version:** 1.0

## Purpose

Group billing is where a well-run group stay either lands smoothly or unravels at check-out. The master folio, the reservation-level folios, and the billing instructions per the group contract must align from the moment the block is built through post-departure reconciliation. This procedure defines how master folios are structured, how charges are routed, and how billing is reviewed and delivered at The Ironwood.

## Scope

Applies to the General Manager (who handles the Revenue Manager and group coordination functions), Front Desk Agents, F&B Supervisor, Spa Manager, and the Accounting team on post-departure reconciliation. Covers all group block reservations. Transient reservations outside a block are not covered.

## Responsibilities

- **General Manager:** Configures master folio and billing instructions in OPERA Cloud at block setup; reviews final master folio before departure; signs off on the final invoice to the group contact.
- **Front Desk Agent:** Posts charges to the correct folio; flags any discrepancy at guest check-out; does not reroute charges without authorization.
- **F&B Supervisor and Spa Manager:** Ensure charges flow to the right folio at the point of sale; verify signatures or room-charge authorization before posting.
- **Accounting:** Generates the final invoice; processes payment; handles any post-departure adjustment with GM sign-off.

## Folio Structure for a Typical Group

A standard group stay at The Ironwood involves three folio types operating in parallel.

### The Master Folio

- Attached to the Group Master record in OPERA Cloud.
- Contains charges the contract specifies the group pays directly: contracted meals, welcome reception, meeting room rental, AV rental, group transportation, contracted amenities.
- Settled to the group's payment method (typically ACH, corporate card, or check per contract) at the end of the stay.

### Reservation-Level Folios (Per Guest)

- One per reservation in the block.
- Contains charges the contract specifies the individual guest pays: room and tax (if guest-pay), incidentals (minibar, spa, additional F&B), parking, any room charge not contracted to the master.
- Settled to the individual guest's payment method at check-out.

### Split Folios

Groups often require split billing — some charges to master, others to guest. Configured at the reservation level via OPERA Cloud's Folio Instruction screen.

- **Example:** Wedding block where the couple pays room and tax on all rooms but guests pay their own incidentals. Folio 1 (master, couple): room and tax. Folio 2 (guest): incidentals.
- Always spot-check split folio setup in the first three reservations processed — a miconfigured instruction repeats across every reservation in the block.

## Step 1 — Configuring Billing at Block Setup

At block setup per the Group Block Setup SOP, the GM configures billing instructions.

1. Open the Group Master in OPERA Cloud.
2. Navigate to Billing Instructions.
3. Select the billing configuration per the contract:
   - Master pays all (rare)
   - Master pays room and tax only; guests pay incidentals
   - Master pays room, tax, and contracted F&B; guests pay all other incidentals
   - Guests pay all; master pays only specific contracted items (catering, meeting room)
4. Enter the master folio payment method. For corporate groups, confirm the credit application or direct bill agreement is on file. For weddings, confirm the card on file is authorized for the projected total.
5. For direct bill (group pays by invoice after departure), confirm the credit application is complete and approved by ownership before the stay begins. Direct bill requires an authorized credit limit.
6. Enter the billing contact — name, email, phone — of the person the final invoice goes to. This is often different from the group's rooming-list contact.

### Common Mistakes at Setup

- Splitting billing between master and guest at the wrong breakpoint — contract says master pays room, tax, and resort fee; GM configures master to pay only room and tax. Every guest at check-out gets charged the resort fee, guest disputes it, manual adjustments cascade through the week.
- Forgetting to disable automatic post of gratuity or service fees to the guest folio when the contract specifies master pays — F&B gratuity is a common miss.
- Configuring the master to pay "all charges" on a wedding block because it's easier — then incidentals the couple doesn't want to cover (expensive bar tabs, spa charges) post to their folio.

## Step 2 — Posting Charges During the Stay

### Room and Tax

OPERA Cloud posts room and tax automatically each night based on the billing instruction. No manual action required.

### F&B Charges

1. At the restaurant, bar, or any F&B outlet, the Server asks: "Will this be going to your room?"
2. If the guest confirms room charge, the Server asks for the room number and a signature.
3. Server enters the room number into MICROS. MICROS interfaces with OPERA Cloud and posts the charge to the correct folio based on the reservation's billing instruction.
4. For group contracted meals (covered by master), the F&B Supervisor ensures the POS ticket is closed to the Group Master code in MICROS, not the guest's room number.
5. For a group event (welcome reception, rehearsal dinner, farewell brunch), the F&B Supervisor confirms the event is routed to master before service starts.

### Spa Charges

1. Spa receptionist confirms the guest's room number and the billing instruction.
2. If the group contract includes spa as master, confirm with the GM before posting to master. Not all wedding contracts cover spa, and assuming does not help.
3. Otherwise, spa charges post to the guest folio by default.

### Incidental Charges (Minibar, Parking, Guest Laundry)

Post to the guest folio unless the contract specifies otherwise. These are almost always guest-pay.

### Charges That Should Go to Master

The GM provides the Front Desk, F&B, and Spa teams a single page at the start of the group listing what posts to master:

> *"Smith-Chen Wedding Group — arrival March 12, departure March 15. Master pays: room and tax on all 28 rooms, welcome reception Friday 6:00 PM, Saturday rehearsal dinner, Sunday farewell brunch. Guests pay: all incidentals including spa, F&B outside the three contracted events, parking, minibar."*

This single page prevents more billing errors than any other document.

## Step 3 — Mid-Stay Folio Review

The GM performs a mid-stay folio audit on any group exceeding 3 nights.

1. On the morning of the second day of the stay, pull the Group Pickup and Folio Summary report in OPERA Cloud.
2. Spot-check five reservation folios for correct charge routing.
3. Review the master folio for expected postings (welcome reception charges should post within 24 hours of the event).
4. Catch and correct misrouted charges now — at check-out is too late.

## Step 4 — Check-Out Handling

### Individual Guest Check-Out

1. FDA pulls the reservation folio in OPERA Cloud.
2. Review only the guest-pay portion of the folio with the guest. Do not display master folio amounts.
3. Confirm the final balance on the guest-pay portion.
4. Process payment.
5. Release the room per the Departure and Check-Out SOP.
6. If the guest questions a charge that should have been routed to master, do not re-route at the desk. Post an adjustment note and hand to the GM for resolution after the guest departs.

### Group Master Check-Out

1. On the group's departure day, the GM reviews the complete master folio.
2. Verify all contracted charges have posted (welcome reception, contracted meals, meeting room, etc.).
3. Verify no charges posted to master that should have gone to guests, and vice versa.
4. Print a draft master folio and present to the group's billing contact for review, either in person or via email depending on the contact's location.
5. Allow the group contact 24 hours to review and question charges.
6. Process adjustments, if any, with GM sign-off.
7. Once the group signs off, the GM closes the master folio.
8. Accounting generates the final invoice.
9. For direct bill: invoice is sent to the billing contact with payment due per contract terms (typically Net 30).
10. For credit card or ACH: payment is processed at master close.

## Step 5 — Post-Departure Reconciliation

See the Post-Departure Group Reconciliation SOP for the formal reconciliation process. Key actions:

1. Archive the final master folio PDF in the group's file.
2. Log the group in the Group Revenue Report.
3. Flag any post-departure adjustment (charge found after the fact, missed posting, late F&B charge) to the GM for resolution within 7 days of departure.

## Documentation

- **OPERA Cloud Group Master record** — primary source of truth.
- **Billing Instructions screen** in OPERA Cloud.
- **Master Folio Summary** — generated at close, archived as PDF.
- **Group Billing Cheat Sheet** (the single page distributed to outlets) — filed in the Group Folder.
- **Final Invoice** — filed in Accounting.

## Escalation Triggers

Contact the GM immediately if:
- A guest disputes a charge at check-out that was misrouted
- Master folio charges are posting above or below the contracted projection by more than 10%
- Direct bill credit application was not completed before the group arrived
- The group's billing contact disputes a line item on the final master review

## Related Documents

- Group Block Setup and Rooming List Processing SOP
- Attrition Clause Tracking and Client Notification SOP
- VIP and Comp Room Assignment for Groups SOP
- Post-Departure Group Reconciliation SOP
- Departure and Check-Out Procedure SOP

## Revision History

| Date | Version | Change Summary | Revised By |
|---|---|---|---|
| [Initial Date] | 1.0 | Initial publication | General Manager |
