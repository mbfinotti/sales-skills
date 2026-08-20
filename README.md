# Skills for Sales teams

> Agent skills for running a sales org and closing the deals in it.

A collection of skills covering **B2B and B2C sales** end to end: market sizing, ICP, quota and comp design at the top, cold calls, discovery, MEDDPICC and negotiation at the deal level.

Built for **SDRs, AEs, sales managers, and heads of sales**.

Every skill produces **a decision or a working artifact**: a scorecard, a cadence, a concession plan, never a generic explainer.

## Related Collections

Other skills repositories I built for my colleague at Nativa Labs:

- [`advertising-skills`](https://github.com/mbfinotti/advertising-skills): Ad platform mastery: _for performance marketers, paid media managers, growth leads_
- [`partnerships-skills`](https://github.com/mbfinotti/partnerships-skills): Partner ecosystem operations: _for partner managers, BD leads, ecosystem heads_
- [`revops-skills`](https://github.com/mbfinotti/revops-skills): Revenue operations: _for RevOps managers, sales ops, marketing ops, CRM admins_

## Install

Install every skill in this repo, not just one. Skills here are atomic by design and reference each other freely: picking a single skill leaves its sibling skills uninstalled, so cross-references and routed handoffs go nowhere.

**skills.sh (universal)**: works with any Agent Skills-compatible tool:

```bash
npx skills add mbfinotti/sales-skills
```

**Claude.ai**: add as a plugin marketplace: open **Settings -> Capabilities -> Plugins**, click **Add -> Add marketplace -> Add from a repository**, enter `mbfinotti/sales-skills`, then **Sync**.

**Claude Code**: install the plugin:

```bash
/plugin marketplace add mbfinotti/mbfinotti
/plugin install sales-skills@mbfinotti
```

**Codex (OpenAI)**: install via the Codex CLI:

```bash
codex plugin add github:mbfinotti/sales-skills
```

**Cursor**: copy into Cursor's skills directory:

```bash
git clone https://github.com/mbfinotti/sales-skills.git ~/.cursor/skills/sales-skills
```

Cursor auto-discovers skills from `.agents/skills/` and `.cursor/skills/`.

**Gemini CLI**: install as a Gemini extension:

```bash
gemini extensions install https://github.com/mbfinotti/sales-skills
```

Update with `gemini extensions update sales-skills`.

## Skills

This collection covers the full sales surface. Start here:

- [`sales-kickoff`](./sales-kickoff): Routes any broad or ambiguous sales request to the one skill that fits, then bootstraps the project's shared sales-context file.
- [`sales-career`](./sales-career): Coaches a candidate through breaking into sales, SDR-to-AE promotion, interview prep, and evaluating an offer against dated benchmarks.
- [`sales-hiring`](./sales-hiring): Builds the employer-side hiring loop: outcome scorecard, structured interview bank, scored mock-call work sample, 30-60-90 ramp plan.
- [`sales-org-structure`](./sales-org-structure): Designs role mix, topology, SDR-to-AE ratio, hunter/farmer split, and span of control for the team's current stage.
- [`sales-radar`](./sales-radar): Assembles a dated, verified watch list of sales podcasts, newsletters, communities, and benchmark reports matched to your role and time budget.

### Market & targeting

| Skill | Description |
| --- | --- |
| [`sales-icp-definition`](./sales-icp-definition) | Defines the ideal customer profile with weighted scoring criteria, explicit disqualifiers, and a refresh cadence, from closed-won data or founder discovery. |
| [`sales-market-sizing`](./sales-market-sizing) | Estimates TAM, SAM, and SOM by triangulating top-down, bottom-up, and value-theory methods, capped by a realistic sales-capacity ceiling. |
| [`sales-account-segmentation`](./sales-account-segmentation) | Builds the weighted account fit score from firmographic, technographic, and intent signals, calibrated on 12 months of closed-won deals. |
| [`sales-account-tiering`](./sales-account-tiering) | Sets tier cutoffs above an existing fit score, with accounts-per-rep caps, a coverage model per tier, and recalibration cadence. |

### Motion & planning

| Skill | Description |
| --- | --- |
| [`sales-motion`](./sales-motion) | Chooses between product-led, sales-led, hybrid, developer-led, or channel motions, and plans the transition between them. |
| [`sales-quota-setting`](./sales-quota-setting) | Derives quotas by reconciling top-down targets with ramp-adjusted capacity, over-assignment cushion, and territory-weighted fair-share allocation. |
| [`sales-comp-design`](./sales-comp-design) | Designs the comp plan - pay mix, performance measures, accelerator curves, SPIFs, draws - with role plans for SDR, AE, manager, overlay, and CSM. |
| [`sales-pipeline-coverage-modeling`](./sales-pipeline-coverage-modeling) | Derives the coverage ratio a team actually needs from its win rates, then converts the gap into new-pipeline-required with in-quarter timing. |

### Outbound prospecting

| Skill | Description |
| --- | --- |
| [`sales-outbound-sequence`](./sales-outbound-sequence) | Plans the touch-by-touch cadence - channel per day, spacing, multi-threading, exit and recycle rules - with the rep capacity math behind it. |
| [`sales-outreach-personalization`](./sales-outreach-personalization) | Turns prospect signals into 2-3 ranked outreach angles, each pairing a dated sourced signal with a hook, an ask, and a confidence label. |
| [`cold-email-subject-line-tester`](./cold-email-subject-line-tester) | Generates angle-distinct subject line variants, scores them numerically, and returns a split-test plan with sample size and decision metric. |
| [`cold-email-deliverability`](./cold-email-deliverability) | Audits sending setup and draft mechanics for inbox placement: SPF/DKIM/DMARC alignment, sender reputation, body hygiene, regional compliance. |
| [`cold-call-opener`](./cold-call-opener) | Writes the first 5-30 seconds of a live cold call for a named persona and pain, with testable variants, delivery notes, and a measurement plan. |

### Discovery & qualification

| Skill | Description |
| --- | --- |
| [`sales-discovery-questions`](./sales-discovery-questions) | Builds a sequenced pain-to-urgency question set sized to the call length, with follow-up ladders, branch triggers, and a do-not-ask list. |
| [`meddpicc-scorecard`](./meddpicc-scorecard) | Scores one deal across the eight MEDDPICC elements on an evidence ladder, returning a verdict band and the single gap-closing next action. |
| [`deal-champion-mapping`](./deal-champion-mapping) | Maps the buying committee from call notes and CRM activity, naming champion, economic buyer, and blockers with confidence tied to observed behavior. |
| [`deal-red-flags`](./deal-red-flags) | Scans one deal's notes and activity for qualification risks, grading each on severity and confidence with the quoted evidence behind it. |

### Deal execution

| Skill | Description |
| --- | --- |
| [`sales-objection-handling`](./sales-objection-handling) | Diagnoses what an objection really means and writes rebuttals a rep can say out loud: or calls the deal dead when the constraint is real. |
| [`deal-value-calc`](./deal-value-calc) | Builds the ROI case for one deal - value drivers, payback, three scenarios - with every number labeled buyer-supplied, benchmark, or rep-assumed. |
| [`negotiation-concession-planner`](./negotiation-concession-planner) | Prices every tradeable lever by cost-to-us vs value-to-them, pairs each give with a required get and approval level, and sets the walk-away. |
| [`sales-meeting-recap`](./sales-meeting-recap) | Converts raw call notes into a recap email where every next step carries an owner, a date, and a deliverable, inventing no commitment. |
| [`sales-call-review`](./sales-call-review) | Grades one call transcript against an anchored rubric, quoting the transcript for every judgement and naming one focus behavior. |

## License

MIT © 2026 Maya-Beth Finotti
