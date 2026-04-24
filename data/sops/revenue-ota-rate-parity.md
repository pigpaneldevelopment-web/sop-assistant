# OTA Channel Rate Parity Audit

**Property:** Ridgeline Lodge, Steamboat Springs, CO
**Department:** Revenue Management
**Document Owner:** General Manager
**Version:** 1.0

## Purpose

Rate parity — ensuring the rate displayed on the property's direct website matches or beats the rate on third-party channels (Expedia, Booking.com, Hotels.com) — is both a contractual requirement with OTA partners and a commercial priority. A lower rate on an OTA site than on the direct site damages direct booking performance and invites contract penalties. This procedure defines how the General Manager at Ridgeline Lodge audits rate parity, diagnoses disparities, and resolves them.

## Scope

Applies to the General Manager (holding the Revenue Manager function). Covers all public-facing OTA channels and the property's direct booking engine. Does not cover private or opaque channels (Hotwire, Priceline Name Your Own Price), which have separate parity rules.

## Responsibilities

- **General Manager:** Performs the parity audit weekly; investigates disparities; executes corrective action.
- **Front Desk Agent:** Flags any guest report of an OTA rate lower than the direct rate; passes to GM within same shift.
- **Ownership:** Informed of any material parity breach that could trigger OTA contractual action.

## Why Parity Matters

### Commercial

- Direct bookings are the most profitable channel — no OTA commission, best guest data, strongest loyalty pathway.
- If an OTA shows a lower rate than the direct site, rate-sensitive shoppers book via the OTA. The property loses 15–20% of the rate to commission and loses the direct relationship.

### Contractual

- Most OTA contracts include rate parity clauses. Some are narrow (must not be cheaper on the direct site than on the OTA); some are broad (must not be cheaper on any channel).
- Violations can trigger de-ranking of the property on the OTA's search results — a direct and severe commercial harm.
- Repeated violations can trigger contract review or termination.

### Regulatory

- Rate parity regulations have changed in several markets (EU, UK, Australia). The US is less regulated but watch for developments.
- The property's OTA contracts set the specific parity obligations; the GM references those contracts, not general industry descriptions.

## Weekly Audit Sequence

The GM performs a full parity audit every Tuesday. Tuesday is chosen because OTAs have completed weekend rate updates and the audit catches any Monday-posted weekend disparities.

### Step 1 — Select Audit Dates

Audit 6 specific dates:

1. Tonight
2. Tomorrow
3. Saturday of this week
4. 14 days from today
5. 30 days from today
6. A peak date within the next 90 days (holiday, long weekend, known event)

This mix catches both near-term and forward-posted disparities.

### Step 2 — Gather Direct Rates

1. Open the property's direct booking engine.
2. Search each audit date for a 1-night stay, 2 adults, standard king room.
3. Record the rate shown, including any tax/fee display differences.
4. Repeat for one additional room type (standard queen or junior suite) per date.

### Step 3 — Gather OTA Rates

1. Open Expedia. Search the property and each audit date with matching parameters.
2. Record the rate shown.
3. Repeat on Booking.com.
4. Repeat on Hotels.com.
5. For each rate displayed, note the total at checkout — OTA display rates may exclude taxes and fees that surface at payment.

### Step 4 — Compare

Build a parity comparison table for each audit date:

| Date | Room Type | Direct | Expedia | Booking | Hotels.com | Parity? |
|---|---|---|---|---|---|---|

"Parity" is met when:
- Direct rate is less than or equal to the lowest OTA rate (per contract definition), OR
- Direct rate is equal to OTA rate (no channel advantage)

"Breach" is identified when:
- An OTA rate is lower than the direct rate by any amount.
- Do not ignore a $1 disparity. Small disparities indicate upstream data issues that compound.

### Step 5 — Investigate Breaches

For each breach identified:

1. Check the OPERA Cloud rate plan. Is the same rate plan pushed to all channels?
2. Check the channel manager (OTA Insight or SiteMinder — at Ridgeline Lodge, SiteMinder). Is the rate update executing correctly?
3. Check each OTA extranet for any promotion, member rate, or package that could explain the lower price:
   - Is the OTA showing a "Member Exclusive" or "Logged-In Only" rate? This is typically allowed under parity (closed user group exception) but confirm per contract.
   - Is there a bundled rate (room + breakfast) that displays as total and appears lower?
   - Is an active OTA-funded promotion running where the OTA is discounting without property involvement? Rare but possible.
4. If the breach is caused by a property error (incorrect rate code, missed rate update, misaligned restriction), resolve immediately:
   - Update the rate in OPERA Cloud.
   - Push through SiteMinder.
   - Verify the push completed.
   - Re-check the OTA display within 2 hours.
5. If the breach is caused by the OTA itself (an unauthorized discount, a mis-posted promotion), contact the OTA market manager:
   - Email the OTA market manager with screenshots and a request to correct.
   - CC the GM at Ridgeline Lodge.
   - Request a response within 48 hours.

## Mid-Week Spot Checks

Between weekly audits, the GM performs 5-minute spot checks Monday, Wednesday, and Friday:

1. Check tonight's rate on the direct site vs. Expedia.
2. Check Saturday's rate (if weekend is nearby).
3. If a disparity is found, full investigation as above.

## Guest-Reported Disparity

If a guest or FDA reports seeing a lower rate on an OTA:

1. Capture the screenshot or URL the guest referenced.
2. Recreate the search parameters.
3. Investigate per the breach sequence.
4. If the property's direct site is legitimately higher, honor the OTA rate for the guest and acknowledge the issue. The property's best-rate guarantee (if in place) supports this action.
5. Document the incident and resolve the upstream parity issue.

## Rate Update Hygiene

Most parity issues trace back to rate update discipline. The GM follows these practices to prevent breaches.

### Single Source of Truth

1. All rate decisions originate in IDeaS G3 (the revenue management system) and flow to OPERA Cloud.
2. OPERA Cloud pushes to SiteMinder.
3. SiteMinder pushes to all OTAs and the direct booking engine.
4. Never update a rate directly in an OTA extranet — this creates a disparity the next time the channel manager runs.

### Update Timing

1. Rate updates are made during the daily rate review (see Daily Rate Review and Yield Decision Procedure SOP).
2. Any update made outside the review is logged in the Yield Log with reasoning.
3. Updates made after 6:00 PM local time should be verified the next morning since OTA caching can delay visibility.

### Restriction Management

1. Minimum length of stay restrictions must be identical across channels.
2. Closed-to-arrival restrictions must be identical across channels.
3. An MLOS of 2 on the direct site but 1 on an OTA creates a different total rate display and triggers parity issues even if the nightly rate matches.

## Documentation

- **Parity Audit Log** — weekly Tuesday audit captured as a dated entry in the shared Revenue drive.
- **Breach Log** — separate log for any breach, with cause, resolution, and time to resolve.
- **OTA Market Manager Communications** — emails archived in the OTA folder per channel.
- **Yield Log** — referenced when a rate update is the cause of a breach.

## Monthly Review

On the first Monday of each month:

1. Review the Breach Log for the prior month.
2. Identify recurring breach types (same OTA, same date pattern, same cause).
3. Address root causes. A recurring breach on a specific OTA may require a contract conversation.
4. Note any OTA market manager response quality — slow responses from a specific OTA impact the property's ability to maintain parity.

## Common Failure Modes

- Skipping the audit during a busy week — the week skipped is usually the week a breach goes live.
- Resolving a breach by updating the rate in the OTA extranet rather than through the upstream system — creates a new disparity at the next channel manager sync.
- Not capturing screenshots when a breach is found — makes investigation harder later if the rate has since resolved.
- Assuming "member rates" on OTAs are always parity-compliant without checking the specific contract definition.

## Escalation Triggers

Contact ownership if:
- A breach involves a material nightly dollar disparity (more than $25) sustained over multiple audits
- An OTA market manager is unresponsive after two outreach attempts
- An OTA contract review or de-ranking threat is received
- A systemic channel manager issue requires vendor engagement

## Related Documents

- Daily Rate Review and Yield Decision Procedure SOP
- Forecast Revision Workflow SOP
- Competitive Rate Shop Procedure SOP
- Overbooking Management and Walk Procedure SOP

## Revision History

| Date | Version | Change Summary | Revised By |
|---|---|---|---|
| [Initial Date] | 1.0 | Initial publication | General Manager |
