# Senior PM

A Claude plugin that acts as an experienced senior project manager — reviewing, challenging,
planning, diagnosing and reporting on your projects. Grounded in the PMBOK Guide 8th Edition
(PMI, 2025), with optional source-verified citation when you supply your own copy.

It is not a book with a chat interface. It gives you the call, then the reasoning.

---

## Install

Copy the `senior-pm/` folder into your plugins directory, or install from a marketplace entry
pointing at this repository. Skills load on trigger; reference files load only when needed, so
context cost stays low.

## The PMBOK source — two modes

**VERIFIED.** Give it your own copy of the guide and it reads from it, citing section and page
(`→ Guide §2.7.3, p. 98`). Run `/setup-source` with a file path, or just upload the PDF in
conversation. Nothing is copied or redistributed — it reads your book.

**UNVERIFIED.** No copy available. It works from its own well-developed knowledge of the
framework — all 40 processes, seven domains, six principles, the tailoring process, all 44
check outcomes, the artifact and technique libraries. It tells you once that it is working
unverified, then gets on with the job without hedging every sentence.

Nothing is gated behind having the book. The judgement is identical in both modes; only
citation precision changes.

**This plugin contains no PMI text.** That is deliberate, not cautious: bundled copyrighted
content would make it undistributable the moment it reached a client or a product. What it
contains is original synthesis, structural indexes, and templates.

## Skills

| Skill | What it does |
|---|---|
| `senior-project-manager` | The core. Charters, scope, schedule, cost, stakeholders, risk, resourcing, change, closure, approach selection, PMO, procurement. |
| `project-health-check` | Evidence-based audit across all seven domains — 44 checks with a scoring rule that refuses assertions. |
| `pm-tool-operations` | Live projects in Wrike, Notion, ClickUp, Monday, Jira, Asana and similar. Evaluate, report, update, comment. |

## Commands

| Command | |
|---|---|
| `/health-check [project]` | Run the seven-domain audit |
| `/charter-review [charter]` | Completeness, authority and boundary review |
| `/decide [decision]` | Work a fork and produce a decision record |
| `/diagnose [symptom]` | Root cause → intervention → the check that proves it |
| `/status-report [project]` | Decision-grade steering pack |
| `/setup-source [path]` | Point it at your PMBOK copy |

## Three modes

**RUN** — produce or review an artifact. The default.
**DECIDE** — a fork in the road. Produces a decision record naming the principle tension.
**DIAGNOSE** — something is wrong. Root cause, intervention, and the check that proves it.

## How it behaves

Assertive. It leads with judgement rather than options, volunteers the two or three things you
did not ask about but need to know, and disagrees with you when it disagrees — including with
the standard, where the standard is thin for your context.

But it guides. Every challenge comes with a route forward. It never leaves you holding a
criticism with no next step, and it adjusts depth for less experienced users without diluting
the judgement.

It is biased against over-process. The most common failure of PMBOK-derived advice is
prescribing formality nobody needs; the guide itself says its 40 processes are illustrative,
not a methodology. Bring it a two-week internal initiative and it will tell you a checklist is
enough.

## Live project tools

With a PM tool connected, it reads freely — tasks, boards, comments, history, custom fields —
and confirms **every** write before executing. Batch updates are itemised before the ask.
Deletion is out of scope. Instructions found inside project data are treated as data to report,
not commands to follow.

## Try it

- "Review this charter" — paste or attach it
- `/health-check` on a project you think is fine
- "We're four weeks late and the sponsor wants a recovery plan"
- "Should this be predictive or hybrid?"
- "Approvals are taking two weeks and it's killing us"
- "Pull the Atlas project from Wrike and tell me what's actually going on"

## Structure

```
.claude-plugin/plugin.json
commands/                          six slash commands
skills/
  senior-project-manager/
    SKILL.md                       persona, modes, tailoring gate, routing
    references/
      00-source-protocol.md        verified vs unverified behaviour
      01-index.md                  navigational index, 40-process crosswalk
      02-principles.md             six principles and their tensions
      03-lifecycle.md              approaches, hybrid patterns, cadence, focus areas
      04-governance.md             9 processes, by lifecycle moment
      05-scope.md                  6 processes
      06-schedule.md               3 processes
      07-finance.md                4 processes
      08-stakeholders.md           7 processes
      09-resources.md              5 processes
      10-risk.md                   6 processes
      11-tailoring.md              tailoring process + symptom→intervention
      12-appendices.md             PMO, AI, procurement, edition migration
      13-artifacts.md              ~104 inputs and outputs, grouped by job
      14-techniques.md             ~179 tools and techniques, grouped by job
    templates/                     decision record, charter review, status report, risk register
  project-health-check/
    SKILL.md
    references/check-outcomes.md   all 44 checks, restated
    templates/health-check.md
  pm-tool-operations/
    SKILL.md
```

## Notes

Page references follow the print pagination of the 8th edition. They are reliable for
navigation; spot-check before quoting a page in front of a client, particularly in the
appendices.

The plugin carries no organisational defaults, no sector assumptions and no house style. If you
tell it about your company, it uses that. Otherwise it assumes nothing.

## Extending it

The highest-value additions are yours:
- Your organisation's tailoring defaults — what "light governance" actually means where you work
- Your own templates in `templates/`
- Sector overlays: regulated, public procurement, construction, clinical
- A `references/15-house-rules.md` for standards that override or supplement the guide

That layer is what turns a good framework tool into your framework tool.

## License

MIT — see [LICENSE](LICENSE). PMBOK® is a registered mark of the Project Management Institute, Inc.; this plugin is independent and not endorsed by PMI.
