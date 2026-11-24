# Venture Desk | Build blueprint
Private workspace for Mohammed. GitHub is canonical; Google Drive is for requested sharing snapshots. The online school is a separate venture.

## Two entry points
**Find opportunities for me** takes a profile, income target, available hours, platform familiarity, market and previous runs. Generate 4–6 distinct offers across sectors, then shortlist three.
**Investigate my idea** accepts buyer, painful event, proposed outcome and existing assets. Find the strongest substitute and at least one competing opportunity. Both routes create a run ID and use the same evidence, pricing, approval and results process.

## Screens and data
| Screen | Fields and behaviour |
|---|---|
| Profile and launch | Skills, assets, jurisdiction, weekly capacity, hourly cost, accessible buyers, budget, target. Start either route; copy profile assumptions into a dated run. |
| Opportunity board | Run ID, opportunity ID, buyer role, sector, trigger, proposed offer, competitors, status, score, key unknown, cheapest next test. Keep rejected candidates searchable. |
| Evidence | Evidence ID, opportunity, claim, publisher, URL, observed date, source date, geography, buyer segment, currency, scope, amount, evidence type and caveat. Types: payment, contract award, budget, asking price, self-report, interview and unknown. |
| Compare | Scores and weights, pilot price, licence payer, build/sales/support hours, overhead, contribution, target counts and capacity. Show cash and time-adjusted profit separately. |
| Offer and tasks | Offer version, buyer, scope, exclusions, deposit/price, demonstration, measure and approval. Task ID, predecessor, owner, due date, completion evidence and status. |
| Venture Ledger | Date, opportunity/offer ID, pseudonymous prospect ID, stage, quote, payment, recurring amount, hours, tools cost, objection and follow-up. Keep amounts quoted and received separate. |
| Dashboard and playbooks | Show next buyer action, strongest evidence, untested assumption, pipeline by stage, cash collected, actual hours, economic profit, approved next task and review date. Link reusable handovers to a versioned offer. |

## Roles and reusable prompts
1. **Venture Researcher:** “For this buyer and outcome, find UK payment or award evidence, budgets and supplier asks. Return one sourced claim per row with date and buyer size. Mark missing categories unknown.” Hand evidence IDs to Analyst.
2. **Venture Analyst:** “Apply stored weights. Calculate cash and time-adjusted margin, customer counts and downside at double support time. Cite evidence IDs. Name what would reverse rank one.” Hand ranked candidate and falsification test to Builder.
3. **Offer Builder:** “Draft one fixed-scope pilot, buyer qualification, price, exclusions, test fixture, acceptance criteria and outreach draft. Label assumptions.” Mohammed approves or sends back for revision.
4. **Venture Tasker:** “For the approved offer version, assign dependency-ordered tasks with completion evidence and review dates. Separate draft outreach from authorised sending.” Hand results to Ledger.
5. **Venture Ledger:** “Reconcile quotes, receipts and delivery time; summarise objections and actual margin. Propose repeat, revise or stop, with evidence.” Mohammed records decision.
6. **Delivery Playbook:** On repeat decision capture proposal, supported connectors, configuration, test fixtures, fallbacks, customer handover, maintenance terms, observed cost and version. Use synthetic fixtures; store secrets separately.

## Build choices
| Option | Indicative cost | Fit and maintenance |
|---|---|---|
| Google Workspace, Sheets and AppSheet | AppSheet Starter $5 or Core $10/user/month at list; check included Core entitlement and underlying Workspace plan. Gemini/API usage varies. | Fast mobile forms, low maintenance. Adds synchronisation if GitHub is canonical. Useful as a client delivery choice. [AppSheet](https://about.appsheet.com/pricing/) |
| Microsoft Lists, Power Automate and optional Power BI | Existing M365 entitlement may suffice for basic features; Premium £11.50/user/month and BI Pro £10.80/user/month on annual plans excluding VAT where required. Base subscription extra. | Best customer demo for first offer. Tenant permissions and connector licensing increase support demands. [Power Automate](https://www.microsoft.com/en-gb/power-platform/products/power-automate/pricing) |
| Private local web app with a checked-out GitHub repo; managed hosting later | Proposed v1 £0 incremental hosting with existing computer/account and manual research. Optional hosted Worker paid tier starts at $5/month before excess usage, domain, identity or model costs. | Recommended for the desk itself: use versioned JSON/CSV or Markdown in the private repo, local forms and a generated dashboard. Manage code and backups through git. Hosted version needs authentication, authorisation, durable storage and backup testing. [Cloudflare D1](https://developers.cloudflare.com/d1/platform/release-notes/) |

## Build sequence and acceptance
1. Manual first run: use the revenue plan as input; keep research claims and assumptions in versioned Markdown. Deliver a priced offer before coding screens.
2. After a second run, define versioned run/opportunity/evidence/offer/event IDs. Add schema validation, required URLs/dates for sourced claims, positive hours and currency validation; deduplicate imports by source and claim. Test an empty dataset and conflicting sources.
3. Build the two entry forms and comparison calculator locally. Recompute targets for the selected period; return “reprice” when margin is nonpositive. Test £750, £25 costs, 12 total hours and £35/hour gives £305 before shared overhead.
4. Add approvals, tasks and ledger. Store corrections as new events; reject duplicate payment imports. Allow draft/approved/sent/paid transitions with observed evidence. Retry-safe writes and revision checks prevent double-counting or overwriting edits.
5. Build phone dashboard and playbook export. Confirm search by buyer/sector, private access, rollback, restore and exclusion of personal data from sharing exports. Automate only repetitive steps observed in actual runs.

## Worked first run
RUN-001 begins with Find opportunities for me. Researcher records UK prices and FCA award evidence in the revenue plan. Analyst compares five offers and recommends the training enquiry pilot, conditional on validating buyer access. Builder prepares £750 scope and five fictional enquiries. Proposed next task: Mohammed reviews scope and identifies ten prospects. Ledger begins with zero recorded offers sent, payments or customers. No sale is inferred from a demo. In a test-only simulation, a £750 receipt and £25 cash cost plus 12 hours produce £305 economic contribution; actuals stay empty until the event occurs. Run Investigate my idea on Dealer Desk using its repo and competing dealer pricing; compare scores to RUN-001. This tests both entry points before building integrations.