# Compliance, Risk And Review Rules

## Minimum Compliance Review

Check intended use, user, patient/student population, output, decision impact, registration scope, labeling, promotional wording, clinical evidence, approved medical service items, reimbursement assumptions, data authorization, retention/deletion, minors, cross-institution sharing, and cross-border transfer.

Treat the following as stop conditions until professional review and evidence are complete:

- diagnosis, treatment recommendation, closed-loop control, or efficacy claim beyond the confirmed scope;
- unapproved healthcare reimbursement or equipment-as医保 claims;
- processing or exporting medical, biometric, patient, or minor data without a documented legal basis and access control;
- severe injury, suspected reportable adverse event, systematic report error, or undisclosed quality issue;
- unauthorized data trading or treating raw data as profit;
- SLA or installation promises unsupported by the current team and service partners.

## Risk Item

Use:

`id`, `category`, `market`, `transaction`, `cause`, `event`, `consequence`, `evidence`, `probability`, `impact`, `inherentScore`, `controls`, `owner`, `kri`, `yellowThreshold`, `redThreshold`, `response`, `residualScore`, `status`, `reviewDate`.

Score probability and the highest material impact on a 1-5 scale. Zero-tolerance safety, registration, privacy, minor-consent, and adverse-event-reporting issues remain major regardless of average score.

## Reviewer Checklist

- Reproduce the decision from the source data.
- Check that documents, workbook, and page use one model.
- Check no source is described as current when it is historical or incomparable.
- Check customer benefit, payer, budget, payback, and no-buy reason.
- Check formulas for unit, sign, double-counting, and cash timing errors.
- Check empty, missing, unknown, and error states in interactive outputs.
- Check claims and data handling against intended use and authorization.
- Return blocking findings with file location, reproduction steps, root cause, minimum fix, and verification.
