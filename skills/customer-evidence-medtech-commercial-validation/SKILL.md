---
name: customer-evidence-medtech-commercial-validation
description: Use when evaluating a medical technology, rehabilitation, biomechanics, sports-health, education-health, or embodied-intelligence product line from customer need through paid-pilot validation, compliance, unit economics, risk gates, and go/no-go decisions. Trigger for business plans, GTM plans, customer ROI, pricing, 1-3 year forecasts, hospital access, subscription/lease models, data-asset claims, or an interactive decision package.
---

# Customer Evidence Medtech Commercial Validation

## Purpose

Turn a broad product-line idea into an evidence-led operating decision. The skill coordinates existing specialist skills; it does not replace regulatory, clinical, financial, sales, or engineering judgment.

The required order is:

> customer value -> evidence -> transaction -> delivery burden -> compliance/risk -> company economics -> continue, adjust, or stop

Never reverse this order by starting with company revenue or market size.

## When To Use

Use this skill when a user needs to:

- validate a medical, rehabilitation, biomechanics, sports-health, education-health, To C, or embodied-intelligence product line;
- turn research and product material into a practical sales or business plan;
- compare purchase, lease, financing, subscription, project, channel, insurance, or joint-operation models;
- connect customer ROI, hospital access, reimbursement, regulatory boundaries, after-sales capacity, and 1-3 year forecasts;
- decide whether a solo founder or small team should run a pilot, hire, expand, or stop.

Do not use it as a substitute for a customer interview, a hospital医保办 decision, a registration opinion, a clinical study, a legal review, or an executed contract.

## Core Workflow

1. **Define the decision.** State the decision owner, target customer, time horizon, geography, product scope, intended use, non-goals, available resources, and what counts as success.
2. **Segment by workflow.** Separate medical rehabilitation, research/sports university, school/education, community/chain institution, and To C/B2B2C. Do not mix family reports with the education market.
3. **Build the customer proof map.** For every segment record: workflow pain, current workaround, buyer, payer, budget source, purchase trigger, objection, customer benefit, payback mechanism, required proof, and next validation action.
4. **Create an evidence ledger.** Label each input as `Known`, `Public evidence`, `Customer-confirmed`, `Inferred`, `Assumed`, or `Missing`. Record source, observation date, access date, comparability limits, and confidence.
5. **Constrain the first 90 days.** Choose no more than two primary regions and three active transaction motions unless the user supplies evidence and delivery capacity for more. Default gate: 15 high-quality interviews, 6 demos or workflow observations, 3 formal quotes, 1 paid pilot, 2 budget-confirmed intents, and 1 end-to-end delivery loop. These are targets, never invented actuals.
6. **Call specialist skills selectively.** Use the routing table below. Load only the references needed for the current decision.
7. **Model customer economics first.** Calculate customer investment, approved service contribution where applicable, labor/time savings, research or quality value, recurring use, direct service cost, payback period, and reasons not to buy.
8. **Model company economics second.** Separate hardware, lease, subscription, report, project, maintenance, channel, financing, and data-service revenue. Link each to quantities, prices, direct costs, delivery capacity, cash timing, and renewal. Do not count raw data as profit.
9. **Apply compliance and risk gates.** Check intended use, registration scope, claims, reimbursement, data authorization, minors, clinical safety, MAUDE limitations, contract ownership, SLA capacity, credit, and cash exposure. A zero-tolerance event cannot be averaged away by a good score elsewhere.
10. **Make the operating decision.** Output `Continue`, `Adjust`, `Pause`, or `Stop`, with conditions, owner, deadline, evidence still missing, and the next smallest experiment.

## Specialist Routing

| Decision need | Specialist skill |
|---|---|
| Pain, buyers, budget and interviews | `market-pain-mining` |
| Hospital access,医保, DRG/DIP, procurement | `hospital-access-pricing-reimbursement` |
| Intended use, FDA/NMPA/MDR and testing | `global-medtech-regulatory-classification` |
| Clinical evidence, recalls and MAUDE | `clinical-evidence-maude-mining` |
| Hardware/software/service/data pricing | `data-moat-pricing` |
| Laboratory-to-field feasibility | `sim-to-real-feasibility` |
| Installation, SLA, tickets and service margin | `after-sales-service-system` |
| Sales/demo/repair records and replay | `record-replay-sales-review` |
| Solo-founder capacity and hiring triggers | `solo-founder-team-building` |
| Three-stage medical-to-robotics pathway | `medical-to-robotics-business-model` |
| Interactive decision delivery | `interactive-pitch-deck` |

If a specialist conclusion conflicts with customer evidence, surface the conflict; do not silently average it away.

## Role Modes

### CEO

Use this skill to define the decision, select the narrowest viable customer wedge, set the 90-day evidence gate, approve or reject transaction structures, and issue a task brief to the coder and reviewer. The CEO must not present assumptions as traction or approve expansion without customer proof.

### Coder

Use this skill to turn an approved evidence model into documents, spreadsheets, dashboards, or Sites. Preserve source links, formulas, editable assumptions, historical snapshots, and the distinction between actuals and targets. Add tests for every decision gate and dynamic calculation. Do not invent customer evidence or alter the commercial decision without returning to the CEO.

### Reviewer

Use this skill to independently check traceability, customer-first ordering, formula integrity, regulatory wording, evidence freshness, privacy boundaries, empty states, and whether the claimed decision is supported by actual data. Block delivery when a forecast is presented as fact, when customer benefit is missing, or when a red-line compliance risk has no owner and response.

## Required Output

Produce a concise decision package containing:

1. Decision and scope.
2. Customer proof map and customer ROI.
3. Evidence ledger with facts, assumptions, gaps, and dates.
4. 90-day validation funnel and acceptance gate.
5. Transaction and pricing matrix with buyer-side economics.
6. Delivery, team, and after-sales capacity.
7. Compliance and risk register with stop conditions.
8. Current formula forecast plus historical/pressure scenarios clearly separated.
9. Recommended decision: continue, adjust, pause, or stop.
10. Next actions with owner, due date, and evidence required.

When building artifacts, keep one source of truth for business-model data. The same inputs must drive the document, workbook, and interactive page. See [evidence-and-gates.md](references/evidence-and-gates.md), [customer-roi-and-finance.md](references/customer-roi-and-finance.md), and [compliance-risk-and-review.md](references/compliance-risk-and-review.md) when needed.

## Non-Negotiable Guardrails

- No customer demand, budget, paid pilot, or revenue is claimed without evidence.
- Market size is an opportunity boundary, not a customer count, sales forecast, or profit.
- Equipment revenue is not医保 revenue. Map healthcare value to approved service items and local confirmation.
- Raw medical, health, biometric, student, or patient data is not automatically a tradable asset or accounting profit.
- Public prices are references; internal proposed prices and cost floors must be labeled separately.
- MAUDE signals identify failure or injury patterns; they do not establish incidence rates or brand safety rankings.
- Do not make diagnosis, treatment, efficacy, or reimbursement claims beyond confirmed intended use and registration scope.
- Do not promise an SLA, installation, calibration, or repair capacity unavailable to the current team.
- Do not create a long plan when the smallest useful next experiment can answer the uncertainty.
