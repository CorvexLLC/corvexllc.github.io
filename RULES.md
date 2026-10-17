# Rules

Rules for checking station log entries against run ticket photos.

1. **Temperature** — the log must use the ticket's **observed temperature** (Obs. Temp), not tank top/bottom temp or average line temp.
2. **Gravity** — the log must use the ticket's **observed gravity** (Obs. Grav), not corrected gravity.
3. **BS&W** — minimum is **0.05**. If the ticket prints less than 0.05, the log should show 0.05. A logged value below 0.05 is an error.
4. **Crude type** — set by observed gravity: above 50 = **Condensate**, below 33 = **Sour**, otherwise **Sweet**. The crude type printed on the ticket does not decide it.

## What to check

- Check **every** field against the ticket photo, not just the numbers: customer (purchaser on the ticket header), producer/operator, lease name, trucking company, driver name, crude type, ticket number, date, gross and net barrels, observed gravity, observed temperature, and BS&W.
- **Ignore** meter number and confirmation code.

## Known name mappings (not errors)

- **Customer:** every Ride The Lightning CTB (Phoenix Operating) ticket is customer **MV Purchasing**, even when the ticket paper says United Energy Trading, LLC or prints no purchaser.
- **Trucking company:** "Vertex Logistics USA" on a ticket = "Vertex Oilfield Services" in the log.
- **Lease name:** small differences are fine (e.g. well number left out, "MICHELLE LAUREN #1H" vs "Michelle Lauren 17-20 #1H").
- **Driver name:** first name, nickname or partial last name is fine (e.g. "Joan c" for Joan Caraballo, "Danny" for Daniel).
