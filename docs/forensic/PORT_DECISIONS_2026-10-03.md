# VIKRAM v0.1 — Port / Rebuild / Quarantine Decisions

## Decision rule

Do not copy the reference repository wholesale.

| Area | Decision | Reason |
|---|---|---|
| V15 accumulation engine | PORT | Canonical engine; frozen |
| V15 config | PORT after hash verification | Frozen semantics |
| Scanner engine | PORT after parity verification | Real backend implementation |
| Scan materializer | PORT after parity verification | Real materialization path |
| PIT/security master | PORT selectively | Historical correctness dependency |
| Survivorship | PORT selectively | Anti-survivorship requirement |
| Corporate actions | PORT selectively | Historical correctness dependency |
| Historical Verdict Store | REBUILD/PORT after schema verification | Required for immutable history |
| Immutable Events | REBUILD/PORT | Required for T0/P0 and outcome lineage |
| Catch → Outcome engine | REBUILD | Must be explicitly built around verified historical detections |
| Catch Frequency Dashboard | REBUILD | Read-only downstream V15 observability |
| Self-Scorecard | REBUILD | Requires immutable historical outcomes |
| Historical Analogue | PORT | Research engine exists |
| Market Regime | PORT + DATA-GATED | Existing engine is a proxy, not official index regime |
| Sector intelligence | PORT + DATA-GATED | Existing mapping is sparse |
| Accumulation DNA | PORT/VERIFY | Backend implementation exists |
| False Accumulation | PORT/VERIFY | Backend/research implementation exists |
| Signal DNA | PORT/VERIFY | Backend/research implementation exists |
| Hidden Gems | PORT + RESEARCH/DATA-GATED | Existing service/engine exists but HGI validation is incomplete |
| RSI | PORT | Research/filter-only; must not alter V15 |
| Research/ASM | PORT + VERIFY | Real research infrastructure exists |
| Walk-forward/OOS | REBUILD/VERIFY | Research requirement; no production claim |
| Recommendation Engine | REBUILD | Not a complete user-facing production capability |
| Recommendation Delta/Lifecycle | REBUILD | Historical decision lineage required |
| Forward Outcomes | REBUILD | Must consume verified historical data |
| News & Events | REBUILD | Real permitted source pipeline required |
| Portfolio | PORT selectively | Browser-local/partial architecture exists |
| Alerts | PORT selectively | Delivery must be verified |
| Position sizing | PORT as deterministic calculator | Not a validated recommendation methodology |
| Live data | PORT architecture only | Provider dependency |
| Data Trust | REBUILD | System-wide evidence/status contract |
| Capability Registry | REBUILD | Needed as v0.1 source of truth |
| Evidence formatter | REBUILD | Enforce Missing != Zero |
| What Changed | REBUILD | Must compare actual published snapshots, not lookback periods |
| Company workspace | REBUILD | New approved UX architecture |
| Website shell | REBUILD | New seven-domain IA |
| Academy | REBUILD | Current content is not built |
| Market Intelligence UI | REBUILD | Current page is honest shell only |
| VIKRAM Lite | PORT/VERIFY | Existing downloader/control inventory requires audit |
| Five-year acquisition | PORT/VERIFY + external execution | Existing tooling requires network-capable environment |
| Oracle acquisition package | PORT tooling, not results | Package exists but no live acquisition result yet |
| V16 | QUARANTINE | Experimental; never merge into V15 |
| Legacy aggregator company/financial data | QUARANTINE | Provenance is not suitable as authoritative V15 evidence |
| Synthetic fixtures | KEEP ONLY IN TESTS | Never production data |
| Render deployment | QUARANTINE | User preference is free/no-paid-Render; deployment must be reconsidered |
