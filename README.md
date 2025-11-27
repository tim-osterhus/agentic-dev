# Agentic Development Frameworks
Agentic development here means running LLMs as Builder and QA agents with clear markdown guardrails: tasks, expectations, and history logs. Each profile turns a general-purpose coding model into a small, disciplined team. Choose the footprint that matches your constraints, then adapt the templates to your tools and repos.

| Framework | Optimized For | Key Features | Typical Use Case |
| --- | --- | --- | --- |
| framework_light | Minimal overhead, single session | Builder + QA cycles, lean tasks/history, scoped roles | Solo contributor or fast fixes |
| framework_balanced | Mix of automation and control | Prompt-engineering pre-cycle, autoscheduler, GitHub push loop | Iterative feature work with light automation |
| framework_heavy | Maximum throughput and oversight | Multi-session orchestration, deep QA, resource/credit awareness, web/CLI agents | Large backlogs, parallel agents, constrained budgets |

## Who This Is For
- Individual engineers wanting a disciplined AI-helper loop.
- Teams experimenting with agentic coding before adopting full orchestration stacks.
- Anyone needing markdown-first handoffs between Builder and QA personas.

## What This Is NOT
- Not a hosted service or SaaS product.
- Not a production-grade orchestrator; it’s a template repo.
- Not tied to any domain, vendor, or stack—fill in your specifics.

## Getting Started
Pick the profile closest to your use-case, read its README, and adapt the markdown cycles to your environment. Tune prompts, roles, and workflows to match your repositories, branching model, and tooling.
