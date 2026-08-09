# Evidence And Decision Gates

## Evidence Record

For every material claim, record:

`claim`, `type`, `value`, `unit`, `region`, `observationYear`, `publishedAt`, `accessedAt`, `source`, `grade`, `isEstimate`, `comparabilityNote`, `owner`, `nextCheck`.

Use these types:

- `Known`: supplied by the user or verified in local product material.
- `Public evidence`: traceable public source with date and scope.
- `Customer-confirmed`: interview, budget confirmation, quote, contract, payment, or delivery record.
- `Inferred`: reasoned interpretation from evidence; explain the inference.
- `Assumed`: editable planning input, never a fact.
- `Missing`: not yet known; do not fill with zero unless zero is a verified observation.

## 90-Day Gate

Default target for a single-owner product line:

| Evidence | Target | Acceptable proof |
|---|---:|---|
| High-quality interviews | 15 | Decision-maker or workflow-owner notes |
| Demos/workflow observations | 6 | Demo record, pain, objection, next step |
| Formal quotes | 3 | Configuration, price, payment, acceptance, expiry |
| Paid pilot | 1 | Contract/order and actual payment |
| Budget-confirmed intents | 2 | Budget source, owner, timing, next action |
| End-to-end delivery loop | 1 | Installation, training, report, acceptance, ticket, review |

The gate is passed only when the paid pilot, two budget intents, and delivery loop are all evidenced. If not passed, recommend `Adjust` or `Stop expansion`; do not automatically add more cities, channels, or headcount.

## Decision Quality Checks

- Does every active scene have a payer and budget source?
- Does the customer benefit occur before company revenue in the explanation?
- Can a customer recover the investment without assuming unapproved reimbursement?
- Are actuals, targets, assumptions, and historical snapshots visually and structurally distinct?
- Is each unresolved uncertainty paired with a smallest next experiment?
