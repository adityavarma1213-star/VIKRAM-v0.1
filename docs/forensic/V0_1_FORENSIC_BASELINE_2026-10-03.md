# VIKRAM v0.1 — Forensic Foundation Baseline
Date: 03 October 2026

## Scope

This is a read-only forensic comparison of the new VIKRAM-v0.1 repository against the current reference repository adityavarma1213-star/Vikram and the approved VIKRAM blueprint/roadmap family available in the project record.

No legacy production code or market data is being copied by this audit.

## Reference repository evidence

Reference repository HEAD verified:
- Repository: adityavarma1213-star/Vikram
- Main commit inspected: 610c488b2183ae9cab39a0727096b2b329413fda
- Default branch: main
- Repository visibility: public
- Recursive tree inspected: 1,255 entries

The reference repository contains substantial application, backend, research, data, tests, and deployment material. It is therefore treated as a source/reference repository, not as an automatically trusted v0.1 baseline.

## Blueprint evidence

The current deep-reconciled blueprint family explicitly states that the blueprint is a specification/roadmap and that listing a feature does not prove implementation or production verification.

The blueprint preserves:
- V15 frozen analytical framework
- trusted historical-data foundation
- PIT universe/security master
- corporate actions and survivorship handling
- immutable events and Historical Verdict Store
- Hidden Gems/HGI
- A/D and participant OI intelligence
- research/ASM/OOS and robustness validation
- recommendation/outcome intelligence
- portfolio/risk sizing
- live-data architecture
- Data Trust/observability
- VIKRAM Lite
- five-year historical requirement
- approved seven-domain website architecture
- RSI multi-timeframe research filter
- V15 Catch Frequency Dashboard
- release/acceptance gates

## Verified implementation findings

### A. V15 canonical accumulation engine — KEEP / PROTECT

Reference path:
- accumulation/engine.js

The backtest audit identifies this exact file as the production engine and records SHA-256:
ae6a8f1f6698fc41d16d7c15800ca7f406361f3f6ef06bc3e04dd43287fedf58

The audit states the engine was imported unchanged by the backtest adapter and its dedicated test suite passed 6/6.

Decision:
- KEEP
- PORT only after an independent hash check in v0.1
- Never rewrite or simplify
- V15 behavior remains frozen

### B. Scanner engine/materialization — KEEP, forensic port

Reference paths:
- server/src/scannerEngine.js
- server/src/scanMaterializer.js

These are real backend components and are candidates for controlled porting. They must remain subordinate to the frozen canonical accumulation engine and must pass V15 parity tests before activation.

Decision:
- PORT after freeze verification

### C. Historical Analogue — KEEP AS RESEARCH ENGINE

Reference:
- backtest/lib/historicalAnalogueEngine.js

This is implemented backend/research code with no-look-ahead and historical-boundary protections. It is not automatically a complete user-facing product.

Decision:
- PORT as research capability
- keep data-gated until verified historical data exists

### D. Market Regime — KEEP AS DATA-GATED RESEARCH

Reference:
- backtest/lib/marketRegimeEngine.js

The implementation explicitly describes itself as a cross-sectional breadth/volatility/equal-weight proxy rather than an official NIFTY/index regime series.

Decision:
- PORT only with explicit PROXY/DATA-GATED semantics
- do not label as official benchmark regime without verified benchmark data

### E. Sector Accumulation/Rotation — KEEP ENGINE, DO NOT FABRICATE

Reference:
- backtest/lib/sectorAccumulationEngine.js
- backtest/lib/sectorLookup.js

The engine refuses to fabricate when sector coverage is insufficient. Current verified mapping is sparse.

Decision:
- PORT engine
- quarantine production UI until verified sector mapping/data are sufficient

### F. Research Intelligence — KEEP AS RESEARCH

Reference:
- backtest/lib/researchIntelligence.js

The engine computes ASM statistics across defined horizons and uses sample-size-aware confidence tiers without invented numbers.

Decision:
- PORT as research layer
- not claim full Research Intelligence product until UI, provenance and real-data validation are complete

### G. RSI Multi-Timeframe — PORT AFTER VERIFICATION

Reference evidence includes:
- js/rsiEngine.js
- data/rsi-snapshot.json
- tests/rsiFilter.test.js

The RSI capability is a research/filter layer and must not alter V15 scoring or confirmation logic.

Decision:
- PORT as filter-only capability
- preserve Daily/Weekly/Monthly RSI(14), direction and zone behavior
- no V15 scoring changes

### H. Five-year backtest/acquisition — CRITICAL BLOCKER

Reference backtest README explicitly states:
- REAL NSE DATA: FAIL
- VIKRAM ENGINE: PASS
- BACKTEST: FAIL because the production gate refuses zero real records
- software tests are synthetic mechanics only

The acquisition architecture exists, but the five-year archive is not proven complete.

Current controlled baseline:
- target sessions: 1,238
- present/usable baseline previously audited: 1,167
- missing: 71
- delivery-invalid: 7
- direct-NSE byte-verified acquisition: 0 until independently proven
- archive complete: NO
- Oracle one-session test: not yet executed

Decision:
- BLOCK production historical claims
- acquire genuine NSE data before historical outcome claims

### I. Performance Lab — PARTIAL

Reference performance-lab.html explicitly states:
- 1-Year Research is the genuinely implemented capability
- Recommendation Archive, Research & Validation Lab, Framework Evolution are not yet implemented

Decision:
- PORT 1-Year Research
- REBUILD/complete later research layers

### J. Market Intelligence — UI ONLY / DATA-GATED

Reference market-intelligence.html explicitly states that Sector Leaderboard, Sector Rotation, Market Heatmaps, Market Breadth and macro/regime context require data not currently ingested.

Decision:
- PORT shell only if useful
- rebuild data-backed intelligence later

### K. Academy — UI ONLY

Reference academy.html explicitly states that lesson content has not been built.

Decision:
- REBUILD curriculum
- do not copy placeholder shell as a claim of completion

### L. News & Events — NOT PRODUCTION VERIFIED

A news calculation engine exists in the reference repository, but its existence does not prove a real permitted news-ingestion pipeline.

Decision:
- REBUILD around free/permitted/real sources
- authoritative identity mapping
- source URL, event type, publication time, ingestion time and provenance
- no paid API dependency
- no prohibited NSE scraping
- no silent V15 scoring change

### M. Portfolio / Alerts — PARTIAL

Portfolio and alert UI/backend pieces exist, but delivery/persistence and provider verification are not uniformly proven.

Decision:
- PORT selectively
- verify before claiming live delivery

### N. Live market architecture — BACKEND / EXTERNAL DEPENDENCY

Reference repository contains live-data gate/token/provider/instrument-mapping components, but legitimate provider credentials and production connectivity are external dependencies.

Decision:
- PORT architecture only
- DATA SOURCE BLOCKED until legitimate provider is configured and verified

### O. Data Trust / provenance / observability — PARTIAL

Reference repository contains checksum, validation, ingestion and provenance-related components, but the v0.1 system must make status explicit and enforce Missing != Zero.

Decision:
- REBUILD as a first-class v0.1 control layer
- use two-axis status:
  - Freshness
  - Evidence state

## Important integrity finding

The reference repository contains a repo-wide CHECKSUMS.json, but the later forensic review found it is a broad manifest rather than a suitable permanent V15 freeze list. v0.1 must use a dedicated frozen-file manifest after the authoritative V15 files are independently verified.

## Performance finding

The reference static scanner snapshot is large and contains substantial period data. v0.1 should not simply reproduce the legacy page-load pattern. A derived summary/detail architecture should be measured before implementation.

## Final baseline decision

VIKRAM-v0.1 is NOT a fork-by-copy.

It is a clean reconstruction governed by evidence:

KEEP → verified component
PORT → verified implementation
REBUILD → useful but incomplete
QUARANTINE → data/provenance/dependency blocked
REJECT → unsupported/duplicate/unsafe

No production claim is made by this document.
