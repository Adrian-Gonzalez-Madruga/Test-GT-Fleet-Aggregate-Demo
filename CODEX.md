# Codex Project Guide

## Purpose
This file is the primary operating context for Codex in this repository.
Codex should read this file at the start of each run and keep it current.

## Core Documents
- `CODEX.md`: application context, architecture, and Codex runbook.
- `TECHNICAL_RULES.md`: implementation constraints, engineering standards, and technical guardrails.
- `BUSINESS_RULES.md`: product/domain behavior, policy rules, and business constraints.

## Basic Application Architecture
The application should follow a clear layered architecture:
- Presentation Layer: UI/views, routing, and interaction logic.
- Application Layer: use cases, orchestration, and workflow coordination.
- Domain Layer: core business entities, invariants, and business logic.
- Infrastructure Layer: persistence, external APIs, queues, and framework adapters.

Data flow should follow:
- User/System Input -> Presentation -> Application -> Domain -> Infrastructure -> Response.

## Codex Operating Instructions
On every run, Codex should:
1. Read `CODEX.md`, `TECHNICAL_RULES.md`, and `BUSINESS_RULES.md` first.
2. Use these files as the default source of truth for implementation decisions.
3. Update this file with relevant project knowledge that improves future execution.
4. Add or refine technical constraints in `TECHNICAL_RULES.md` when learned from prompts, code, or inferred patterns.
5. Add or refine business/domain rules in `BUSINESS_RULES.md` when learned from prompts, behavior, or inferred intent.
6. Keep updates concise, specific, and non-duplicative.

## Cumulative Learning Log (Keep Updated)
Use this section to capture durable learnings that improve future runs.

### Learned Context
- Initial baseline created. No project-specific architecture details have been provided yet.

### Next Known Gaps
- Confirm actual tech stack (frontend/backend/framework/runtime).
- Confirm data model and integration boundaries.
- Confirm deployment/runtime environments.
