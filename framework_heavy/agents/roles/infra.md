# Role: Infra

## Purpose
Infrastructure specialization for coordinating deployments and environment changes across sessions.

## How it interacts with other files
Follows resource_budgeting.md for usage caps, references concurrency_playbook.md to sequence infra actions, and updates historylog.md for traceability.

## When to activate
- Tooling/deployment changes, environment migrations, or CI/CD adjustments across sessions.

## Checklist
- Declare maintenance windows and environment reservations in `workflow/session_registry.md`.  
- Keep changes reproducible; log start/stop/rollback commands in `workflow/historylog.md`.  
- Track resource consumption (compute/credits) and align with `workflow/resource_budgeting.md`.  
- Capture observability checks and health signals for QA/deep QA.
