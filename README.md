# Hardik Tiwari

Principal Product Manager, and AI builder at Intuit. Currently building autonomous tax savings agents at Intuit and multiplayer AI tools for open source projects


[LinkedIn](https://www.linkedin.com/in/hardik-tiwari/) · [Writing](https://medium.com/@hardiktiwari) · [tiwari.hardik36@gmail.com](mailto:tiwari.hardik36@gmail.com)

---

## Open source

### PM OS — agentic toolkit with a context graph for product managers

**Creator** · [`PM-operating-OS`](https://github.com/hardiktiwari/PM-operating-OS)

An operating system for PMs running on Cursor and Claude Code. Supplies the model with persistent product context so sessions do not start cold.

- `AGENTS.md` — persistent persona, learned user preferences, workspace facts
- `skills/` — 18+ on-demand PM capabilities: PRD authoring, experiment design, launch readiness, decision logging, exec communication
- `knowledge/products/<product>/` — dossier pattern: brief, roadmap, metrics, experiments, releases
- `.cursor/mcp.json` — MCP server integrations (Figma, Google Drive, Jira)
- Continual-learning loop that extracts corrections from conversation transcripts and rewrites the agent persona
- Semantic recall over the knowledge base for retrieval across historical decisions

### Pip — ambient AI harness that enables AI coworker across Slack, desktop, and browser

[`PIP-`](https://github.com/hardiktiwari/PIP-) · [site](https://hardiktiwari.github.io/tandem-site/)

One agent exposed on three surfaces, resolving against a single workspace and a single memory.

- **Engine** — `packages/engine`, one adapter over the Cursor CLI: `runAgent() → cursor-agent -p … --model <any> --workspace <repo>`
- **Model-agnostic** — model selected by environment variable; no per-provider integration path
- **Surfaces** — Slack bot (`@Pip`), floating desktop task widget, page-aware Chrome extension
- **Memory** — local `memory/` directory shared across surfaces; optionally mounts PM OS as a git submodule to load skills and domain knowledge via `AGENTS.md`

### Masker — on-device privacy layer for voice agents

**Co-contributor** · Apr 2026 · [`voice-agents-hack`](https://github.com/hardiktiwari/voice-agents-hack)

Built at the Y Combinator Voice Agents hackathon (Cactus × Google DeepMind). A redaction policy agent for a Gemma 4 voice agent running on-device: classifies each utterance and routes it local-only or masked-send, holding PHI on the device to support HIPAA-sensitive workflows. Hybrid edge/cloud routing with cloud fallback for complex turns.

### Shopify Autoresearch — autonomous PDP optimization loop

[`Shopify-Autoresearch`](https://github.com/hardiktiwari/Shopify-Autoresearch)

Daily hill-climbing loop over product-detail-page copy on live stores: `observe → score → guard → decide → climb → filter → publish`. An LLM proposes variants, measurement selects winners, and a champion floor, canary rollout, and kill switch bound the downside. Shopify app on Remix and Prisma, with a web pixel extension for event capture and a theme app extension for delivery.

---

## Production AI systems

| System | Org | Technique | Result |
|---|---|---|---|
| Year-end close and books-to-tax automation | Intuit | Long-horizon LLM agents with human-in-the-loop; offline evaluation against historical filings | Tax prep time reduced **99.6%** (5 days → 30 min) |
| Tax Savings agent | Intuit | Agent-first, always-on SMB tax planning | Unlocked **$5B+ TAM** |
| Expert matchmaking service | QuickBooks Live | Contextual-bandit policy over expert–customer pairing | **+10 pts NPS**, +1pp 90-day retention |
| NLP extraction and classification | DRAUP | Human-in-loop labeling workflows and model evals | **+50% model accuracy**, +30% deployment efficiency |

---

## Experience

| Role | Organization | Period | Scope |
|---|---|---|---|
| Principal Product Manager, TurboTax Small Business | Intuit | 2023–present | Tax platform serving 36M+ small business owners |
| Product Manager, Meta Connectivity | Meta | 2022 | Connectivity diagnostics for Oculus and FB app |
| Product Manager, QuickBooks Live | Intuit | 2021–2022 | AI+HI bookkeeping service; grew 200%+ in FY22 |
| Head of Product, founding team | WareIQ (YC S20) | 2018–2020 | Led 10 engineers; MVP to 50+ SMB customers, 50,000 orders/month |
| Director of Product | DRAUP | 2016–2018 | Led 25+ eng/DS; concept to $5M ARR; first 10 Fortune-500 logos |
| Engagement Manager | Zinnov | 2013–2016 | Workforce globalization and digital transformation advisory |

---

## Talks and writing

- **[Building Your Team's Context Graph](https://github.com/hardiktiwari/building-your-teams-context-graph)** — talk delivered at SAP, published as an interactive deck.
- **[Giving AI Your Context](https://medium.com/@hardiktiwari)** — two-part series on context systems and self-updating knowledge bases.

---

