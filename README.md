### Hi, I'm Zarek 👋

**GTM engineer.** I build the systems behind pipeline: signal-based prospecting, outbound infrastructure that runs itself, and AI agents that sellers can actually trust, grounded in real data, cited, and gated by a human where it matters.

Currently building the outbound engine for **[Junipr](https://junipr.info)**, an AI phone agent for plumbing companies.

---

### Featured work

| Project | What it does | Built with |
|---|---|---|
| **[outbound-engine](https://github.com/zareklivak/outbound-engine)** | Production cold-email system: idempotent lead import → Instantly, a webhook-fed CRM dashboard, inbox-health monitoring, and a Claude Slack agent whose every write is Approve-gated | Python · Next.js · Supabase · Instantly · Slack · Claude |
| **[readyroom](https://github.com/zareklivak/readyroom)** | Meeting-prep agent: turns ~45 min of discovery-call prep into a 5-min brief where every claim cites its source (CRM, call transcript, news, KB), checked by deterministic evals in CI | Next.js · Claude · evals |
| **[accountiq](https://github.com/zareklivak/accountiq)** | Digital sales room + AE intelligence console: buyer engagement flows into explainable deal signals (momentum, health, new stakeholders) and a grounded meeting-prep brief | Next.js · Redis · Claude · Jest |
| **[signal-outbound-playbook](https://github.com/zareklivak/signal-outbound-playbook)** | A full signal-based outbound motion: intent thesis, lead qualification (with rejects), a 6-touch multichannel sequence, and the system to run it weekly at 10x | Strategy · systems design |
| **[claude-skills](https://github.com/zareklivak/claude-skills)** | Workspace-adaptive Claude Code skills for start/end-of-session operations | Claude Code |

### How I build

- **Deterministic first, LLM on top.** Rules compute the signal; the model explains it. If the model can't cite it, it doesn't say it.
- **Humans approve the writes.** Agents read freely and *propose* actions; a person clicks Approve before anything touches a prospect's inbox or the CRM.
- **The docs are not the API.** I verify every integration live and write down where reality differs.

**Stack I reach for:** TypeScript / Next.js · Python · Postgres (Supabase) · Claude API · Apollo · Instantly · Clay-style enrichment waterfalls · Slack apps · Vercel
