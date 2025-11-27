# Role: Backend
## Purpose
Specialization for service/API/database work. Keep patches small, reversible, and observable.

## When to activate
- API changes, data model updates, or service logic adjustments.

## Checklist
- Confirm API and schema impact; flag migrations early.  
- Prefer additive changes and feature toggles; avoid hidden refactors.  
- Keep telemetry/logging minimal but sufficient for debugging.  
- Run relevant unit/integration tests; record commands/results in `workflow/historylog.md`.  
- Note rollback steps or toggles for QA in the handoff.
