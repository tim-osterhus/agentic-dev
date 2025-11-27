# Resource Budgeting

## Purpose
Track and manage compute, credits, and time to keep multi-session runs sustainable.

## How it interacts with other files
Sets limits that autoscheduler.md and orchestrator.md must honor, informs deep_qa_cycle.md planning, and logs consumption details to historylog.md.

## How to use
- Define budgets and thresholds before scheduling; update when capacity changes.  
- Orchestrator enforces limits; Builders/QA log consumption in `workflow/historylog.md`.  
- Use this to decide when heavy tests or web agents can run.

## Template
- Budget by resource type (compute, credits, time) per session/task  
- Allocation/consumption tracker with thresholds  
- Alerts/flags and who responds  
- Throttling or pause rules when limits are hit  
- Notes for QA/deep QA on costlier test suites
