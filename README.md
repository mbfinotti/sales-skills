# Skills for Sales teams

> Agent skills for running a sales org and closing the deals in it.

A collection of skills covering **B2B and B2C sales** end to end — market sizing, ICP, quota and comp design at the top, cold calls, discovery, MEDDPICC and negotiation at the deal level.

Built for **SDRs, AEs, sales managers, and heads of sales**.

Every skill produces **a decision or a working artifact**: a scorecard, a cadence, a concession plan, never a generic explainer.

## Install

Install every skill in this repo, not just one. Skills here are atomic by design and reference each other freely — picking a single skill leaves its sibling skills uninstalled, so cross-references and routed handoffs go nowhere.

**skills.sh (universal)** — works with any Agent Skills-compatible tool:

```bash
npx skills add mbfinotti/sales-skills
```

**Claude Code** — install the plugin:

```bash
/plugin marketplace add mbfinotti/mbfinotti
/plugin install sales-skills@mbfinotti
```

**Codex (OpenAI)** — install via the Codex CLI:

```bash
codex plugin add github:mbfinotti/sales-skills
```

**Cursor** — copy into Cursor's skills directory:

```bash
git clone https://github.com/mbfinotti/sales-skills.git ~/.cursor/skills/sales-skills
```

Cursor auto-discovers skills from `.agents/skills/` and `.cursor/skills/`.

**Gemini CLI** — install as a Gemini extension:

```bash
gemini extensions install https://github.com/mbfinotti/sales-skills
```

Update with `gemini extensions update sales-skills`.

## Skills

This collection covers the full sales surface. Start here:

- [`sales-kickoff`](./sales-kickoff) — Routes any broad or ambiguous sales request to the one skill that fits, then bootstraps the project's shared sales-context file.
- [`sales-career`](./sales-career) — Coaches a candidate through breaking into sales, SDR-to-AE promotion, interview prep, and evaluating an offer against dated benchmarks.
- [`sales-hiring`](./sales-hiring) — Builds the employer-side hiring loop — outcome scorecard, structured interview bank, scored mock-call work sample, 30-60-90 ramp plan.
- [`sales-org-structure`](./sales-org-structure) — Designs role mix, topology, SDR-to-AE ratio, hunter/farmer split, and span of control for the team's current stage.
- [`sales-radar`](./sales-radar) — Assembles a dated, verified watch list of sales podcasts, newsletters, communities, and benchmark reports matched to your role and time budget.

Browse all skills and their descriptions in [`references/skill-catalog.md`](./references/skill-catalog.md).

## Related Collections

Other Nativa Labs skill repositories:

- [`advertising-skills`](https://github.com/mbfinotti/advertising-skills) — Ad platform mastery — _for performance marketers, paid media managers, growth leads_
- [`partnerships-skills`](https://github.com/mbfinotti/partnerships-skills) — Partner ecosystem operations — _for partner managers, BD leads, ecosystem heads_
- [`revops-skills`](https://github.com/mbfinotti/revops-skills) — Revenue operations — _for RevOps managers, sales ops, marketing ops, CRM admins_

## License

MIT © 2026 Maya-Beth Finotti
