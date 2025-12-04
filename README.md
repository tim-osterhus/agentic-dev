# Agentic Development Frameworks
Agentic development here means running LLMs as Builder and QA agents with clear markdown guardrails: tasks, expectations, and history logs. Each profile turns a general-purpose coding model into a small, disciplined team. Choose the footprint that matches your constraints, then adapt the templates to your tools and repos.

| Framework | Optimized For | Key Features | Typical Use Case |
| --- | --- | --- | --- |
| framework_light | Minimal overhead, small tasks or projects | Two-part builder/QA cycle, simple tasks/history logs, scoped roles | Solo work, lightweight tasks, optimized for token efficiency |
| framework_balanced | Supervised single-task workflow with optimized performance | Prompt-engineering pre-cycle, autoscheduler, GitHub push loop | Building out complex features in busy repos, one task at a time |
| framework_heavy | Maximizing for output speed and automation | Multi-session orchestration, deep QA, coordinated hybrid usage of web/CLI agents | Large minor feature backlogs, parallel working agents, concurrent feature development |

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
