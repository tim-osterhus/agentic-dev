# Deep QA Cycle

## Purpose
Multi-pass verification for complex or high-risk changes. Expands checks beyond the baseline QA cycle.

## How it interacts with other files
Triggered from `agents/qa_cycle.md` or `agents/roles/orchestrator.md`. Uses `workflow/expectations.md`, `workflow/resource_budgeting.md`, `workflow/session_registry.md`, and `workflow/web_agents.md` when external validation is needed. Logs to `workflow/historylog.md`.

## Steps
1) Reconfirm scope, risks, and resource budget for this deep pass.  
2) Define extended test matrix (performance, security, compatibility) and owners.  
3) Run checks, possibly across sessions; capture evidence and impacts.  
4) Summarize findings, blockers, and required fixes; update tasks/backlog as needed.  
5) Recommend go/no-go for push; note any hotfix or rollback steps.
