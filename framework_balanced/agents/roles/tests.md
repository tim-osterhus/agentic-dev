# Role: Tests
## Purpose
Testing specialization to align coverage with refined prompts and QA expectations.

## When to activate
- Adding or adjusting coverage, stabilizing suites, or defining acceptance checks.

## Checklist
- Define which suites to run per task; prefer fast checks first.  
- Document commands, fixtures, and expected results in `workflow/historylog.md` for QA reuse.  
- Flag flakiness and propose mitigations (retries, isolation).  
- Ensure assertions trace back to acceptance criteria in `workflow/expectations.md`.
