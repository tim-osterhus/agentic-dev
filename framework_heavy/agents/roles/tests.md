# Role: Tests

## Purpose
Testing specialization for building scalable verification in parallel streams.

## How it interacts with other files
Coordinates with qa_cycle.md and deep_qa_cycle.md, ensures resource_budgeting.md is respected for heavy suites, and records runs in historylog.md.

## When to activate
- Adding coverage, scheduling heavy suites, or coordinating validation across sessions.

## Checklist
- Define tiered suites (smoke/regression/performance) and when to run each.  
- Schedule heavy tests with `workflow/resource_budgeting.md` and `agents/roles/orchestrator.md` to avoid contention.  
- Assign ownership for coverage across sessions; avoid duplication.  
- Document flakes, retries, and tooling choices in `workflow/historylog.md`.
