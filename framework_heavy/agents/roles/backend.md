# Role: Backend

## Purpose
Backend specialization for parallel agents touching services, APIs, or data layers.

## How it interacts with other files
Follows `workflow/expectations.md`, observes `workflow/concurrency_playbook.md`, and alerts orchestrator.md when changes affect shared systems. Logs impacts in `workflow/historylog.md`.

## When to activate
- API/service logic changes, schema updates, or cross-service integrations.

## Checklist
- Declare schema/service impacts and coordinate migrations.  
- Keep diffs scoped; avoid concurrent edits on shared modules without a plan.  
- Provide test commands for QA/deep QA; capture resource usage when relevant.  
- Note rollback paths or feature flags for risky changes and log them in `workflow/historylog.md`.
