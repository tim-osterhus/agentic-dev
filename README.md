# Agentic Development Frameworks

Three profiles of an agentic development workflow: lightweight, balanced, and heavy. Each orchestrates Builder and QA agents with markdown task queues and history logs. The goal is to turn a generic coding LLM into a disciplined, repeatable development "team" with clear handoffs. Pick the profile that fits your constraints and scale it up or down.

| Framework | Optimized For | Key Features | Typical Use Case |
| --- | --- | --- | --- |
| framework_light | Efficiency and minimal overhead | Single-session Builder/QA loop, lean task and history files | Solo contributor, quick fixes or small features |
| framework_balanced | Mix of automation and human control | Prompt-engineering pre-cycle, autoscheduler pull, GitHub push loop | Iterative product work with light automation |
| framework_heavy | Parallelism and maximum throughput | Multi-session orchestration, deep QA, resource budgeting, web agents | Large backlogs with multiple agents and compute resources |

## Getting Started
Pick the profile closest to your use-case, read its README, and adapt the markdown cycles to your environment.
