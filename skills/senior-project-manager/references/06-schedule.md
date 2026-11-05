# Schedule — §2.3, pp. 47–58

The smallest domain: **three processes**, all Planning and Monitoring/Controlling. Key Concepts
p. 47 · Processes p. 48 · Tailoring p. 55 · Interactions p. 57 · Check p. 57. Overview:
Figure 2-20, p. 48.

## Processes

**Plan Schedule Management** (P, p. 49) — policies, procedures and documentation for developing,
managing and controlling the schedule. Includes the rules: what a variance threshold is, when a
date is a commitment versus a forecast.

**Develop Schedule** (P, p. 50) — analysing sequences, durations, resource requirements and
constraints into a schedule model. Steps: **Figure 2-23, p. 51.**

This one process absorbs what the 6th edition split across four (define activities, sequence
activities, estimate durations, develop schedule). Consolidation is convenient but hides the
sub-steps — if a schedule is wrong, diagnose which sub-step failed, because "the schedule is
wrong" is not actionable. Usually it is sequencing (missing dependencies) or duration
estimating (single-point estimates with no basis).

**Monitor and Control Schedule** (M, p. 54) — tracking status and managing baseline changes.

## Techniques
Critical path method `→ §5, p. 161` · critical chain method and CCPM · critical path drag and
drag cost · precedence diagramming relationship types p. 186 · leads and lags p. 180 ·
schedule compression comparison (crash vs fast-track) p. 196 · schedule network analysis ·
resource levelling p. 193 · rolling wave planning · agile release planning · velocity ·
iteration burndown p. 175 · burnup p. 214 · kanban board p. 213 · Monte Carlo simulation
p. 199 · theory of constraints. Network diagram example: `→ §4, Figure 4-2, p. 127`.

**On compression:** crashing adds cost, fast-tracking adds risk and rework. Figure 5-20, p. 196
compares them. Neither creates time; both convert one constraint into another. Say which one
you are converting into what before you recommend it.

## Tailoring — §2.3.3, p. 55
The instrument must match the approach: network-based model predictively, release and iteration
plan adaptively, explicit interface between them in hybrid. Product vision / release planning /
iteration planning relationship: Figure 5-1, p. 147.

Cadence is a separate axis from approach `→ Standard §4.4, p. 69`.

## Interactions — §2.3.4, p. 57
**→ Resources:** durations are a function of who is available at what allocation. A schedule
built before resource estimates is a wish with dates on it.
**→ Risk:** floats, buffers and contingency reserves are the schedule's expression of risk.
**→ Finance:** the schedule drives the funding curve `→ Figure 4-1, p. 126`.

## Check outcomes — Table 2-7, p. 58 (restated)
1. **Scheduling approach matches deliverables** — aligned to predictive, adaptive or hybrid.
2. **Life cycle expressed in phases** — launch to close, with appropriate exit criteria.
3. **Holistic delivery** — no gaps or areas of misalignment across the project.
4. **Documentation complete** — dependencies, durations, resource allocations, milestones, at
   the level the chosen approach requires.
5. **Appropriate tools and techniques used** — e.g. scheduling software, critical path method.
6. **Stakeholders involved in developing it** — low participation from client and team predicts
   an unrealistic schedule. A *leading* indicator, available before the first slip.
7. **Sufficient buffers for known-unknowns** — constraints and known risks reflected as floats,
   contingency reserves, or secondary network strategies.

Items 6 and 7 are where most schedules fail, and both are checkable on day one. A schedule
built alone and buffered nowhere is the standard failure pattern, and you can call it before
anyone has slipped a day.
