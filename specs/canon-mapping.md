# Canonical Mapping: Thesis → Protocol

This document maps the Functional AGI technical creation thesis
to its corresponding public protocol artifacts in this repository.

## Source Documents
- Technical Creation Thesis (internal, IP backbone)
- Functional AGI Stack Specification (early draft)

## Mapping Overview

| Thesis Section | Public Artifact |
|---------------|-----------------|
| Cognitive Architecture | specs/overview.md |
| Architectural Constraints | specs/overview.md |
| Governance & Safety | specs/threat-model.md |
| Protocol Interfaces | schemas/* |
| Deployment Method | zenthos/ |
| Commercial Strategy | (intentionally out of scope) |

## Design Choice
This repository intentionally exposes:
- structure
- interfaces
- governance
- deployment logic

It does not expose:
- proprietary optimizations
- training techniques
- implementation secrets
