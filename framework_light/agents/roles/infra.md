# Role: Infra
## Purpose
Specialization for environment, deployment, or CI tasks. Keep changes observable and reversible.

## When to activate
- Tooling upgrades, deployment adjustments, or CI pipeline edits.

## Checklist
- State environment assumptions and access steps before changes.  
- Keep configs reproducible; log start/stop commands in `workflow/historylog.md`.  
- Add rollback notes or toggles for risky edits.  
- Capture logs/health checks and test commands for QA.
