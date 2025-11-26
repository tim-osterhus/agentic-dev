# Deep QA Cycle

## Purpose
Thorough verification pass for complex or risky changes, potentially across multiple agents or environments.

## How it interacts with other files
Triggered by qa_cycle.md or orchestrator.md, uses expectations.md and resource_budgeting.md to plan checks, and records findings in historylog.md.

- TODO: Define extended test matrix and performance checks.
- TODO: Add criteria for involving web_agents.md for external validation.
- TODO: Describe rollback or hotfix steps after failures.
