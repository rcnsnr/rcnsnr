# Orçun Şener

AI-assisted software delivery · SRE · Platform engineering

I build practical software and automation with a reliability-first approach. My background spans Linux, containers, observability, and incident response; my public projects show APIs, web interfaces, tests, and documented delivery decisions.

## Selected work

### [Job Search Workflow](https://github.com/rcnsnr/job-search-workflow)

Local-first job-search tooling with a Python CLI, FastAPI dashboard, browser extension, and user-controlled AI workflows. Alpha; source-available for noncommercial use.

[Code](https://github.com/rcnsnr/job-search-workflow/blob/main/dashboard/server.py) · [Tests](https://github.com/rcnsnr/job-search-workflow/blob/main/tests/test_dashboard.py) · [Privacy and CI checks](https://github.com/rcnsnr/job-search-workflow/blob/main/.github/workflows/ci.yml)

### [PPTX Brand Reviewer](https://github.com/rcnsnr/pptx-brand-reviewer)

FastAPI + Next.js application for explainable slide-level brand findings and human review. Deterministic checks; no AI runtime dependency.

[Review UI](https://github.com/rcnsnr/pptx-brand-reviewer/blob/main/apps/web/components/review-workspace.tsx) · [Rules](https://github.com/rcnsnr/pptx-brand-reviewer/blob/main/apps/api/src/brand_reviewer_api/services/rules.py) · [Tests](https://github.com/rcnsnr/pptx-brand-reviewer/blob/main/apps/api/tests/test_rules.py)

### [Payment Request Demo](https://github.com/rcnsnr/lovie-afb-assignment)

Next.js/TypeScript + Prisma/PostgreSQL assignment with responsive dashboards, server-enforced lifecycle rules, and Playwright evidence. Payments are simulated.

[Data model](https://github.com/rcnsnr/lovie-afb-assignment/blob/main/prisma/schema.prisma) · [Tests](https://github.com/rcnsnr/lovie-afb-assignment/blob/main/e2e/pay-simulation.spec.ts) · [AI delivery log](https://github.com/rcnsnr/lovie-afb-assignment/blob/main/docs/AI_PROCESS.md)

### [Agentic Infra Notes](https://github.com/rcnsnr/Agentic-Infra-Notes)

Sanitized agent-workflow architecture, local LLM experiments, and operational safety notes. Public documentation rather than private implementation code.

## AI and local LLM work

I use **Claude, Codex, and Devin** for scoped planning, implementation, debugging, and documentation. My delivery approach connects requirements to reviewable changes, automated checks, and human decisions.

The [historical GX10/GB10 lab](https://github.com/rcnsnr/Agentic-Infra-Notes/blob/main/case-studies/botaio-n8n-finetuning-lab.md) documents Arm/Blackwell compatibility, QLoRA-oriented debugging, and memory trade-offs. BOTAIO is on hold. Hermes orchestration is a research/design direction, without a published end-to-end validation result.

## Security and reliability

- Explicit task scope and limited data/credential exposure.
- Tests and review before consequential changes.
- Observable execution and documented failure modes.
- Reproducible setup, recoverable changes, and clear evidence boundaries.

Published test assets describe recorded runs; they do not guarantee current deployment health.

## Contact

[LinkedIn](https://www.linkedin.com/in/orcunsener)
