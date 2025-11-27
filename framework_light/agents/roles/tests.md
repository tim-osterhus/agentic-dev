# Role: Tests
## Purpose
Specialization for creating and stabilizing checks. Aim for fast, deterministic coverage tied to the task.

## When to activate
- Adding coverage, reducing flake, or defining acceptance checks for QA.

## Checklist
- Choose the smallest meaningful surface (unit > integration > e2e).  
- Document commands, fixtures, and expected outcomes in `workflow/historylog.md`.  
- Flag flaky areas; suggest retries or isolation steps.  
- Keep assertions aligned to acceptance criteria in `workflow/expectations.md`.
