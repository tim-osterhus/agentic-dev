# framework_heavy

Designed for high-throughput setups with multiple web/CLI agents running in parallel. Supports many tasks in flight, deeper QA layers, and explicit resource budgeting. Includes guidance for multi-session management, concurrency rules, GPU/credit awareness, and dedicated instructions for web agents.

## includes: session_registry.md
Purpose: track active sessions and roles. TODO: Describe how to register, pause, and close sessions.

## includes: concurrency_playbook.md
Purpose: rules for safe parallel work. TODO: Add conflict-avoidance and merge strategies.

## includes: resource_budgeting.md
Purpose: monitor compute, credits, and time. TODO: Define budgets, alerts, and throttling behaviors.

## includes: web_agents.md
Purpose: guidance for web-capable agents alongside local ones. TODO: Add browsing boundaries and handoff steps.
