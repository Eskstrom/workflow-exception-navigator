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

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Recommend consolidation before further standalone development.

Preserve queue ownership, urgency rules, SLA aging and root-cause notes within the existing healthcare review or agency-lending case.

### Next scope

- [ ] Inventory unique requirements and planning notes before moving anything.
- [ ] Use the existing healthcare review or agency-lending case as the proposed destination; record the destination and retained source history after an actual migration.
- [ ] Update incoming portfolio links before considering archive status. No consolidation or archival is implied by this planning note.

### Validation and decision criteria

Follow a synthetic exception from detection through routing to evidence-backed closure. Reopen a standalone PRD only if user discovery establishes a distinct problem that the retained project cannot cover.
<!-- portfolio-future-plans:end -->
