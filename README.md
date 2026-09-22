# Workflow Exception Navigator

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=healthcare-operations#library)

## Product brief

A triage workspace for operational exceptions. It classifies cases by urgency and root-cause category, recommends the next queue, and records resolution patterns.

## Design focus

Route operational exceptions with transparent urgency, reasons, and ownership.

## Proposed scope

- Synthetic exception records with timestamps, reason codes, and ownership.
- Rule-based routing and priority recommendations.
- Queue view, SLA clock, and resolution notes.
- Analytics by exception type and recurring source problem.

## Validation targets

- A user can understand why a case was routed.
- Queue health and aging are visible without opaque metrics.

## Potential implementation

React/Next.js, TypeScript, SQLite/Supabase.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)
