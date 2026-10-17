# Rules

Rules for checking station log entries against run ticket photos.

1. **Temperature** — the log must use the ticket's **observed temperature** (Obs. Temp), not tank top/bottom temp or average line temp.
2. **Gravity** — the log must use the ticket's **observed gravity** (Obs. Grav), not corrected gravity.
   - **Exception — Topshelf tickets:** use the ticket's **average gravity** and **average temperature** instead of observed.
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

## Station conventions — CPI Stanley Lot 9 (learned from reviewed log, Oct 16–17 2026)

- **Badlands Tank Lines tickets** (Silver Hill, Petro-Hunt): Ticket # = **Carrier Order #** (no trailing "A"). Customer = the **Shipper** (Gunvor / Mercuria). Gross = **EST. GOV**, Net = **EST. NSV**. Gravity/temp = observed. The obs values are often on a second photo (lower half of ticket).
- **Power Fuels tickets** (Hunt Oil, LACT): trucking company is logged as **Wisco**; customer **Mercuria**. Gross = **Gross Barrels** (not Est. Gross), Net = **Net Barrels**. Gravity = **Observed Gty.** (not API Density); temp = **Observed Temp**.
- **Top Shelf Energy tickets** (Hunt, Henry 1-28H): **Avg. Grav** and **Avg. Temp**. Gross = **Gross Barrels**, Net = **Net BBLs**. These print values one line below their labels — check meter end − start = Gross Barrels.
- **Plains meter transfer tickets** (Trenton East Truck Load Out): producer and trucking = Plains Marketing LP; customer from the destination line (e.g. "STANLEY CPI - GUNVOR SOUR" → Gunvor). Gross = Est. Barrels in Transit, Net = Estimated Net BBLs.
- **NGL / natural gasoline tickets** (gas plants, gallons): barrels = gallons ÷ 42; crude type Condensate. A specific gravity like 0.650 converts to API (~86). Temp = average of the compartment temps.

## Station conventions — CPI Beaver Lodge

- **Customer exception:** the **Chord Ray Gas Plant** lease has customer **Mercuria**.

## Not needed

- Do not validate the handwritten LACT sign-in sheets against the online entries unless asked.
