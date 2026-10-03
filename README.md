# VIKRAM v0.1

Clean foundation build of the VIKRAM investment-intelligence system.

## Purpose

VIKRAM v0.1 is a new, controlled repository for the next-generation VIKRAM build. The existing adityavarma1213-star/Vikram repository remains the reference/source repository and is not replaced by this repository.

## Non-negotiable rule

VIKRAM V15 is frozen.

This repository must not alter V15 scoring, weights, thresholds, gates, signal definitions, PIT semantics, survivorship handling, corporate-action semantics, Missing != Zero semantics, or production verdict logic.

## Build principle

Nothing is considered complete merely because an engine, UI, document, or test exists.

Every capability must be classified as:

- KEEP — verified and safe to carry forward
- PORT — verified component to bring into v0.1
- REBUILD — useful capability requiring controlled implementation
- QUARANTINE — exists but data/provenance/architecture is not production-ready
- REJECT — unsupported, duplicate, unsafe, or inconsistent with frozen rules

## v0.1 starting point

The first commit establishes governance and forensic control. Product code and historical data are intentionally not copied blindly from the legacy repository.

Next major dependency: genuine five-year NSE historical-data acquisition and verification.

## Repository relationship

- Reference repository: adityavarma1213-star/Vikram
- New repository: adityavarma1213-star/VIKRAM-v0.1
- V15 analytical framework: frozen
- Five-year archive: not yet complete
- Oracle acquisition test: not yet executed
- Production release: not claimed

VIKRAM-v0.1 is a foundation, not a production release.
