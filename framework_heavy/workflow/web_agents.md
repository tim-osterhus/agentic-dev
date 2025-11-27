# Web Agents

## Purpose
Guidance for agents that can browse or use remote tools alongside local sessions.

## How it interacts with other files
Aligned with expectations.md for safety, coordinated by orchestrator.md for task selection, and logged in historylog.md with resource impacts noted in resource_budgeting.md.

## How to use
- Define allowed sources and sync cadence before enabling web access.  
- Coordinate assignments through `agents/roles/orchestrator.md` and note resource impacts in `workflow/resource_budgeting.md`.  
- Log commands, timestamps, and costs in `workflow/historylog.md`.

## Template
- Allowed data sources/domains and safety rules  
- Sync cadence with local agents; how to hand off findings  
- File I/O rules (what can be written/where) and diff sharing  
- Logging requirements (commands, timestamps, costs) in historylog.md  
- How to avoid duplicating local work; when to involve orchestrator.md
