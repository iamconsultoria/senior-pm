---
description: Run an evidence-based project health check across the seven performance domains
---

Run a project health check using the `project-health-check` skill.

Target: $ARGUMENTS

If no project is named, ask which project — once — and whether it is held in a connected PM
tool or described in chat. If a tool holds it, use `pm-tool-operations` to pull live data and
score evidence rather than assertion.

Establish the tailoring context (approach, governance weight, what triggered the review), then
recommend a scope: full seven-domain audit for a gate, handover or recovery; Risk + Schedule +
Scope for a routine self-check; Governance + Finance + Risk for a steering pack.

Score with the evidence rule: anything asserted rather than seen is Amber. Finish with the
pattern read and three actions with owners and dates. If the project is in trouble, say so in
the first line.
