# ellocharlie

**Stop losing customers to broken processes.**

ellocharlie is the CX + CRM platform for early-stage startups — built by a two-human, five-agent team running on Claude.

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/ellocharlie/.github/blob/main/LICENSE)
[![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-Contributor%20Covenant%20v2.1-4baaaa.svg)](https://github.com/ellocharlie/.github/blob/main/CODE_OF_CONDUCT.md)
[![Security Policy](https://img.shields.io/badge/security-responsible%20disclosure-blue.svg)](https://github.com/ellocharlie/.github/blob/main/SECURITY.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ellocharlie/.github/blob/main/CONTRIBUTING.md)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)
[![Built with Bun](https://img.shields.io/badge/built%20with-Bun-%23fbf0df?logo=bun)](https://bun.sh)
[![Deployed on GitHub Pages](https://img.shields.io/badge/site-GitHub%20Pages-0969da?logo=github)](https://ellocharlie.com)

---

## What We're Building

Most startups lose their best customers not to bad products, but to bad processes — slow responses, missed follow-ups, broken handoffs. ellocharlie is the platform that fixes this: CRM, helpdesk, onboarding, and health scoring in one place, managed by an AI agent team that never misses an SLA.

**Target customer:** Founding teams of 2–10 who can't afford to lose their early adopters.
**Pricing:** $45–$65/seat/month. Blended ARPU: $137.50/customer.

---

## The Org

The ellocharlie GitHub organization runs as an **agent-driven company**. Two humans (Nicholas and Kristine) work alongside five AI agents to build, ship, and operate the product.

### Repositories

| Repository | Purpose | Status |
|-----------|---------|--------|
| [`ellocharlie-engine`](https://github.com/ellocharlie/ellocharlie-engine) | Superrepo — brain, dashboard, agent configs, orchestrator | Active |
| [`ellocharlie.com`](https://github.com/ellocharlie/ellocharlie.com) | Marketing landing page (static HTML/CSS/JS) | Active |
| [`ellocharlie-agents`](https://github.com/ellocharlie/ellocharlie-agents) | Multi-agent runtime, 18 skills, ecforge CLI | Active |
| [`ellocharlie-content`](https://github.com/ellocharlie/ellocharlie-content) | Blog, docs, case studies — MDX content engine | Active |

### The Five Agents

| Codename | Role | Schedule |
|----------|------|----------|
| CEO | Strategy, OKRs, investor updates | Weekdays 9am UTC |
| CTO | Code review, architecture | On every PR |
| Growth | Content, SEO, acquisition | Mon / Wed / Fri |
| CX Lead | Ticket triage, SLA enforcement | Always-on |
| Ops | Deploys, canary, infrastructure | Always-on |

The source of truth for agent configurations, KPIs, OKRs, and infrastructure is [`workspace.yaml`](https://github.com/ellocharlie/ellocharlie-engine/blob/main/workspace.yaml) in the engine repo.

---

## Current Goals (Q2 2026)

1. **Land first 10 customers** through the personal network — NPS > 70, < 24h time-to-value for each.
2. **Ship Phase 1 CX platform** — email + Slack channels, knowledge base, AI triage, account health scoring.
3. **Build the content engine** — 36 blog posts in 12 weeks, 500+ GitHub stars on the open-source agent framework, 10 backlinks from SaaS publications.

---

## Community

We build in public. The agent framework powering ellocharlie is open-source under the MIT license.

- **Website:** [ellocharlie.com](https://ellocharlie.com)
- **Email:** [hello@ellocharlie.com](mailto:hello@ellocharlie.com)
- **Security issues:** [security@ellocharlie.com](mailto:security@ellocharlie.com) — please do not open public issues for vulnerabilities

### Community Health Files

| File | Description |
|------|-------------|
| [CONTRIBUTING.md](https://github.com/ellocharlie/.github/blob/main/CONTRIBUTING.md) | How to report bugs, suggest features, and submit changes |
| [CODE_OF_CONDUCT.md](https://github.com/ellocharlie/.github/blob/main/CODE_OF_CONDUCT.md) | Contributor Covenant v2.1 |
| [SECURITY.md](https://github.com/ellocharlie/.github/blob/main/SECURITY.md) | Responsible disclosure policy |
| [AGENTS.md](https://github.com/ellocharlie/.github/blob/main/AGENTS.md) | Standing orders for AI agents contributing to this org |
| [LICENSE](https://github.com/ellocharlie/.github/blob/main/LICENSE) | MIT License |

---

## Contributing

All repos in the ellocharlie org welcome contributions. The quality bar is high and the standards are explicit. Read [`CONTRIBUTING.md`](https://github.com/ellocharlie/.github/blob/main/CONTRIBUTING.md) before you open a PR.

If you are an AI agent: read [`AGENTS.md`](https://github.com/ellocharlie/.github/blob/main/AGENTS.md) first, then the repo's `CLAUDE.md`, then `workspace.yaml`. In that order.

---

*ellocharlie — founded 2026 — agent-driven from day one.*
