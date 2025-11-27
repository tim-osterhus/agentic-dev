# History Log

## Purpose
Central record of actions, tests, prompt versions, and decisions across all sessions.

## How it interacts with other files
Updated by every cycle, referenced by orchestrator.md for coordination, and informs prompt_engineering_cycle.md for future tasks.

## How to use
- Log after each checkpoint, QA pass/fail, resource change, or push.  
- Include session IDs and commands so other agents can reproduce.  
- Link to `workflow/tasks.md` entries and any external evidence.

## Entry Template
- Timestamp / session ID / agent + role  
- Task reference and prompt version  
- Actions and commands (with results)  
- Resource usage notes (time/credits/compute) if relevant  
- Outcomes (pass/fail/blocker) and next steps  
- Links to diffs, pushes, or follow-up tasks

## Maintenance
- Keep append-only; never rewrite history.  
- Review cadence set by orchestrator.md for coordination meetings.
