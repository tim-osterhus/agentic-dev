# Role: Infra
## Purpose
Infrastructure specialization for configs, CI, and deployments with lightweight automation.

## When to activate
- Tooling updates, pipeline edits, deployment changes, or environment tuning.

## Checklist
- State environment assumptions and access steps up front.  
- Keep changes reproducible; document start/stop/rollback commands in `workflow/historylog.md`.  
- Tie scheduling or pipeline triggers back to `workflow/autoscheduler.md` when relevant.  
- Capture validation evidence (health checks, logs) for QA.
