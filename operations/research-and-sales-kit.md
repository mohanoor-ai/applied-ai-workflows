# Venture Desk research and sales kit

## Start a run in any AI chat

Copy the prompt below. Attach this kit, the latest profile and relevant tracker rows. Keep the working record in the private Venture Desk GitHub project. Use a Google Form for intake and a Sheet as a convenient shared view when needed. Carry dated, anonymised changes back to the opportunity's GitHub record before handing off. Omit personal contact details from shared copies.

### Master prompt

Act as Venture Desk's opportunity analyst. Read the saved profile, intake and previous decisions. Identify the run ID, current stage and decision due. Reuse the evidence already collected and flag anything stale. If I supply a discovery question, rank up to three narrowly defined offers and create a separate opportunity row for each. If I supply an idea, investigate it directly. If I supply buyer feedback or delivery results, resume that stage under the same ID.

Use the stage instructions below. Prefer UK buyer evidence and existing customer software. Show sources, dates, evidence type and limitations. Mark unknowns. Compare demand, buyer access, time to first sale, startup spend, labour and recurring income. Explain the ranking and identify which missing fact could change it. Price a bounded GBP pilot and calculate the economics before and after paying for founder time. State the riskiest assumption, cheapest practical buyer test, spending limit and decision rule. Draft outreach for review. Only record outreach, payments and results that actually happened.

Return a concise recommendation, evidence table, priced pilot, test script, and one tab-separated tracker row per opportunity in the Opportunities column order below. Finish with one next action, owner, due date and evidence needed to advance. On later runs show what changed and why. When browsing or records are unavailable, list precisely what needs checking.

Saved profile: [profile or reference]
Opportunity brief: [form response]
Previous results: [rows, receipts or decision history]
As-of date and current request: [date and task]

## Fixed founder profile

London-based founder with IT, teaching, software and data experience. Prefers remote delivery and established platforms. Has a dealer enquiry tracker demo and access to a tuition operator open to experimenting. Compare routes to £1,000 and £3,000 monthly profit. Longer-term aspiration of 10k per month requires confirmation of currency and take-home target. Confirm available hours and founder hourly rate before relying on margin estimates. AI workflow automation is one candidate. Keep the online school in its own project.

## One intake form

Capture these six answers once per opportunity: What are we investigating? Who might buy? What can we already demonstrate? Which platforms should we compare? What deadline and spending cap apply? What decision must this run support? Assign a stable ID on review. A discovery question can leave buyer and platform open.

## Stage instructions and handoffs

| Stage and skill | Work to perform | Record and advance when |
|---|---|---|
| Research / Venture Researcher | Search for the buyer's own description of the problem, a comparable purchase, a published budget, competing prices and the current workaround. Compare the existing CRM or tools with Google Workspace, Microsoft 365 or another suitable provider. Record licence tier, who pays, access needed and setup effort. | Save dated source rows. Explain why this buyer is reachable, what remains unknown and the cheapest way to check it. |
| Design / Offer Builder | Write “For [buyer], we will deliver [specific change] within [time] for £[price].” Specify inputs, deliverables, exclusions, support period, acceptance measure and baseline. Estimate sales, build, delivery and support hours separately. | Save a one-page pilot and a demo with sample data. Lock the offer version before testing. |
| Test demand / Venture Tasker | Ask how the last real case was handled. Show the relevant part of the demo. Ask who approves spending and offer a specific price and start date. Log each prospect's reply and next step. | Count distinct prospects contacted, replies, quotes, purchases and objections. A compliment or a free trial counts as feedback. Advance to delivery on a confirmed order. Record payment separately. |
| Deliver / Venture Ledger | Agree starting baseline and measurement window. Log actual setup, support, tools, fees, revenue received, refunds and buyer outcome. Obtain acceptance or document the shortfall. | Compare estimate with actuals. Record whether the buyer would renew, refer or buy again and what evidence supports it. |
| Decide / Venture Analyst | Repeat when the outcome and margin justify another sale. Revise one variable when evidence points to a specific barrier. Drop when tests undermine the core assumption. Use On hold for a real dependency. | Record decision, reason, owner, next action and review trigger. For Repeat, package the demo, proposal, pricing, setup checklist, reusable components, acceptance test and handover in a Delivery Playbook. |

## Tracker layout

One spreadsheet, one header row per tab. Join records by opportunity ID. Use dated events so the history survives changes of stage.

- Profile: field, value, last confirmed date.
- Opportunities: ID, parent discovery ID, buyer, offer, stage, status, biggest unknown, next action, owner, due date.
- Evidence: ID, source date, accessed date, URL or private reference, geography, evidence type, claim, amount and currency, limitation. Types: third-party completed purchase, buyer budget, advertised price, buyer interview, estimate. Keep own transactions in the Ledger.
- Buyer tests: ID, offer version, prospect alias, date, event, price quoted GBP, objection or feedback, next step. Track contact, reply, demo, quote, order and loss separately.
- Ledger: ID, order reference, period, cash received GBP, refunds, direct expenses, sales hours, delivery hours, support hours, baseline, actual outcome, acceptance, evidence reference.
- Decisions: ID, date, repeat/revise/drop/on hold, rationale, metric, owner, review trigger, playbook link.

For a pilot, cash contribution = receipts less refunds and direct expenses. Labour-adjusted contribution = cash contribution less total hours × founder hourly rate. For a monthly goal, divide (goal + monthly shared overhead) by positive contribution per sale and round up. Use monthly contribution per active customer for subscriptions. Check required hours against capacity. If contribution is zero or negative, extra sales at that margin cannot reach the goal.

## First run: dealer enquiry follow-up

Suggested ID DEALER-001. Independent UK dealer with a small sales team. Working tracker demo. Compare the dealer's existing CRM reminders with the proposed tracker. Suggested test envelope: two weeks and £100 maximum. £750 is a price hypothesis. Sales, conversion and actual margin are unknown.

Ask: “When a customer enquires and nobody reaches them first time, how do you know who follows up tomorrow?” Ask for the last example, who owned it and what the CRM already did. If a gap exists, demonstrate assigning one missed enquiry to a salesperson and surfacing it the next day. Offer a two-week pilot for one team and one enquiry source. Agree the baseline and compare the proportion of eligible enquiries with a recorded next-day follow-up. Record the denominator and any change in staffing.

Proposed test gate: approach ten suitable dealers, log the response and seek one paid pilot. If nobody replies, revise access or messaging. If decision-makers see the demo but already solve the problem, record their workaround and reconsider the offer. A payment validates one sale. Repeat only after measuring delivery effort, margin and customer outcome.

Example opening message for review: “How does your team keep track of yesterday's unanswered enquiries? I've built a small tracker for that handover. Would you walk me through how you handled the last one? If there's a gap, I can show you the demo in five minutes.”

Example tracker row (proposed run):

```tsv
DEALER-001	—	Independent UK car dealers	Next-day enquiry follow-up	Research	Open	Does the existing CRM already solve this?	Ask one dealer to walk through their last missed enquiry	Founder	To agree
```

After each run, record the slowest manual step and its frequency. Consider automation once repeated runs show its cost and the inputs and outputs are stable.
