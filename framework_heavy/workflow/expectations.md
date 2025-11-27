# Expectations

## Purpose
Shared standards for quality, communication, and risk management in high-throughput mode.

## How it interacts with other files
Guides builder_cycle.md and qa_cycle.md decisions, informs deep_qa_cycle.md thresholds, and sets rules for web_agents.md usage.

## How to use
- Set this before scheduling; update if risk changes and log in `workflow/historylog.md`.  
- Builders plan against these rules; QA/deep QA validate against them.  
- Orchestrator enforces the communication cadence and escalation paths.

## Template
- Functional and non-functional expectations (performance, security, logging).  
- Approval gates for QA vs deep QA; severity levels for findings.  
- Required tests/commands and evidence before push.  
- Communication cadence and escalation paths across sessions.  
- Out-of-scope items to avoid churn.
