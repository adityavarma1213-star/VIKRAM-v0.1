# VIKRAM v0.1 — Next Gates

## Gate 0 — Forensic baseline
Status: IN PROGRESS

- Reference repository inspected
- Blueprint requirements reconciled at high level
- No legacy code copied
- No V15 change

## Gate 1 — Authoritative V15 freeze manifest
Required:
1. Identify the exact authoritative frozen files.
2. Compute SHA-256 for each.
3. Store the manifest in v0.1.
4. Add a CI parity guard.
5. Prove UI/output parity with the reference implementation.

Do not guess the frozen-file list.

## Gate 2 — Five-year data acquisition
Required:
1. Execute Oracle package preflight.
2. Test exactly one missing session: 2025-05-06 CM.
3. Preserve raw bytes and provenance.
4. Record SHA-256 and validation.
5. Verify the archive ledger is unchanged.
6. Only then scale acquisition.

Expected first-session evidence from the controlled runbook:
- acquired: 1
- still_missing: 70
- delivery_invalid_remaining: 7
- byte_verified: 1
- verification: PASS
- archive_is_complete: false

These are expected acceptance criteria, not claimed results.

## Gate 3 — Historical V15 Catch → Outcome
After verified history exists:
- immutable detection event
- detection date
- detection price
- verdict at detection
- subsequent dates/prices
- T+1/T+5/T+20/T+60/T+120
- return
- MFE
- MAE
- drawdown
- provenance
- universe/PIT state
- corporate-action state

## Gate 4 — Catch Frequency
Build read-only dashboard:
- Confirmed today
- Confirmed this week
- Confirmed this month
- Average/week
- Average/month
- Unique stocks
- Repeat confirmations
- Confirmation rate per scanned stock
- Top confirmation dates
- Zero-confirmation dates and reason

No lookback-period data may be mistaken for daily snapshots.

## Gate 5 — v0.1 application shell
Only after the evidence foundation is protected:
- seven-domain navigation
- Company workspace
- Discover
- Research
- Intelligence
- Portfolio
- Tools & System
- Overview/Home
- market-context strip
- contextual evidence drawer
- six themes with Light/Dark/System requirement
- responsive/a11y

## Gate 6 — Release
Production release requires:
- real-data verification
- historical verification
- browser verification
- security/QA
- V15 parity
- provenance
- performance
- release-gate evidence

Until all required gates pass, v0.1 remains a foundation build.
