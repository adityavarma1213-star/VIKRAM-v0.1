# VIKRAM V15 Freeze

## Status

FROZEN — PERMANENT

VIKRAM V15 is the protected analytical baseline for VIKRAM v0.1 and later software releases.

## Protected

The following must not be changed as part of v0.1 work:

- V15 scoring weights
- V15 thresholds
- V15 confirmation gates
- V15 signal definitions
- V15 verdict logic
- PIT semantics
- survivorship handling
- corporate-action semantics
- Missing != Zero semantics
- production accumulation logic
- V15 analytical outputs

## Software versioning

Software release versions such as v0.1, Beta, and v1.0 are separate from the frozen analytical framework version V15.

Example:

VIKRAM Software v0.1 — V15 Frozen Core

## Change-control rule

Any proposed future framework change must be documented separately as research/experimental work, for example V16, and must never silently modify V15.
