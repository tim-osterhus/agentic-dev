# Concurrency Playbook

## Purpose
Rules for safe parallel work to avoid conflicts, duplicate efforts, and merge pain.

## How it interacts with other files
Informs builder_cycle.md planning, guides autoscheduler.md on collision avoidance, and provides guardrails for orchestrator.md decisions.

## How to use
- List known hotspots and lock rules; keep this current as work shifts.  
- Builders consult before planning; orchestrator enforces during scheduling.  
- Update changes in `workflow/historylog.md` when rules shift.

## Template
- Shared hot spots (files, services) and ownership/lock rules  
- Safe vs risky parallel patterns; when to sequence work instead  
- Conflict detection signals and escalation steps  
- Branching/merging guidelines and review expectations  
- Communication cadence for coordination (standups, async check-ins)
