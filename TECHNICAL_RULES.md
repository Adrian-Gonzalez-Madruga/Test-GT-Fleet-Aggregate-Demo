# Technical Rules

## Source of Rules
This document stores technical constraints learned over time from:
- Explicit user instructions.
- Existing codebase conventions.
- Stable inferred engineering requirements.

## Current Rules
- Prefer layered architecture: Presentation, Application, Domain, Infrastructure.
- Keep business logic out of infrastructure adapters and UI handlers.
- Maintain clear separation of concerns and minimal coupling between layers.
- Update this file whenever new technical constraints are discovered.

## Rule Maintenance Protocol
When adding a rule:
1. State the rule in one clear sentence.
2. Add brief rationale only if needed.
3. Remove or refine outdated rules instead of duplicating.
4. Keep rules testable and implementation-oriented.

## Change Log
- Initial baseline rules created.
