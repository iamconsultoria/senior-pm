# Governance — §2.1, pp. 10–37

Replaced Integration, and is wider: decision rights, oversight, quality assurance, knowledge,
change control, closure. **Nine processes across all five focus areas — the only domain that
spans the whole lifecycle.**

Front matter unique to this domain: Project Value Creation p. 10 · Governance Models p. 11 ·
Metrics and Mechanisms p. 13 · Additional Considerations for Predictive Environments p. 13 ·
Key Concepts p. 14. Structured vs self-governed: Figure 2-1, p. 12. Common governance
scenarios: Table 2-2, p. 11. Insourcing vs outsourcing: Table 2-3, p. 21.

Organised below by **moment**, because that is how the work arrives.

---

## MOMENT 1 — Starting

### Initiate Project or Phase (Initiating)
Formal authorisation; the document tying the project to business objectives.

Only two processes exist in Initiating across the whole standard: this and Identify
Stakeholders. **Project start is a governance act plus a stakeholder act.** Everything else you
are tempted to do at kickoff is Planning wearing a costume.

**What the charter must carry:**
1. Business objective — one sentence, testable
2. Authorisation: who empowers this, **to what numeric limit**
3. Success criteria and how measured `→ Standard §2.1.2, p. 16`
4. Scope boundary, including explicit exclusions
5. Named sponsor, PM, decision forum
6. Constraints and assumptions
7. Headline risk exposure
8. Sustainability considerations, flagged now for decomposition later
9. Funding source and envelope
10. Phase structure with exit criteria

Charter vs scope statement element comparison: **Table 4-1, p. 129.** Use it to stop the
charter swallowing the scope statement — a charter specifying deliverables in detail is
obsolete by the second change.

**Senior PM checks nobody asks for:**
- Is the authority limit a *number*? An unbounded charter delegates nothing and guarantees
  every decision escalates.
- Is the escalation threshold stated — the point where a decision stops being the PM's?
- Who may release contingency reserve, on what evidence?
- Does the sponsor named actually have the authority claimed? Charters routinely name someone
  who cannot fund the thing they are authorising.

**Tailoring:** adaptive contexts may use a project canvas (`→ §5, p. 189`) or one-page vision.
Format is negotiable; **explicit authorisation is not**.

**At phase gates:** the same process re-runs. Prior-phase exit criteria are this phase's entry
evidence.

### Identify Stakeholders
Governance owns authorisation; Stakeholders owns this → `08-stakeholders.md`.

---

## MOMENT 2 — Setting up

### Integrate and Align Project Plans (Planning)
Consolidating each domain's plan components into one plan covering execution, monitoring and
controlling, and closing.

**The value is not the document — it is finding where the domain plans contradict each other.**
Hunt for:
- Schedule assuming resources the resource plan does not fund
- Budget baseline predating the last approved scope change
- Risk responses with no owner in the resource plan and no money in the budget
- Communications cadence that cannot feed the governance forum's decision cycle
- Quality gates absent from the schedule as actual activities
- Procurement lead times not reflected in the critical path

**Produce an alignment matrix, not a bound plan.** Rows = the six other domains; columns =
"what this domain assumes of the others". The contradictions are the deliverable. Nobody reads
a 200-page integrated plan; everybody reads a list of six contradictions.

### Plan Sourcing Strategy (Planning)
Internal vs external resourcing, weighing culture, specialist skills, capacity, risk and the
value proposition. Oversight may sit with the project team or a procurement function.
Insourcing vs outsourcing tradeoffs: Table 2-3, p. 21. Mechanics in Appendix X4 →
`12-appendices.md`.

**Decision frame:** capability (can we?) × capacity (have we room?) × strategic importance
(should this competence stay in-house?) × **risk transfer (does the contract actually move the
risk, or only the blame?)**. The fourth question is the one most sourcing decisions skip, and
the one that surfaces in litigation.

---

## MOMENT 3 — Running

### Manage Project Execution (Executing)
Leading and performing the work in the integrated plans: resources, issues, risks, changes.

### Manage Quality Assurance (Executing)
Ensuring **processes** are performed consistently with expectations. Process-focused, not
deliverable inspection. The only surviving quality process; quality as a discipline lives in
the *Embed Quality* principle `→ Standard §3.5, p. 43`. Cost of quality: `→ §5, p. 159`.

**Diagnostic:** poor deliverable quality → find the process root cause and fix it, rather than
adding inspection steps `→ Table 3-1, p. 112`. Adding verification to a broken process makes it
slower and still broken. Say this out loud when someone proposes another review gate.

### Manage Project Knowledge (Executing)
Using existing knowledge and lessons, and generating new knowledge during delivery.

**Lessons learned are continuous, not terminal.** The governance check outcomes are explicit
that lessons must be captured *during* the project `→ Table 2-5, p. 37`. A lessons-learned
workshop held only at closure is a compliance artifact — everyone has left, nobody remembers,
nothing changes.

### Monitor and Control Project Performance (Monitoring and Controlling)
Tracking, reviewing and reporting progress against objectives. Dashboards `→ §5, pp. 190–191` ·
information radiator p. 174 · EVM Table 5-1, p. 207 · TCPI p. 206.

The governance check outcomes list what leadership should stay apprised of: operational status
and progress, resource requirements, known risks with response plans and escalation criteria,
strategic and operational assumptions, benefits realised, decision criteria and tracking,
change control, compliance with corporate and legal policy, information and communications
management, issues and issue responses, and project funding and financial performance
`→ Table 2-5, p. 37`.

**That list is a ready-made steering committee agenda.** Most steering packs cover status and
finance and nothing else, which is why steering committees discover problems late.

### Assess and Implement Changes (Monitoring and Controlling)
Managing changes including impact assessment and disposition. Example flow: Figure 2-11, p. 30.

**A change request is never one domain.** Assess against Scope, Schedule, Finance, Stakeholders,
Resources and Risk before disposition — the Scope check outcomes require exactly this
cross-domain impact record `→ Table 2-6, p. 46`.

Predictive → change log. Adaptive → backlog management with re-prioritisation. Same process,
different instrument. In adaptive settings the check is *rate*: how fast scope is being added
against how fast it is being completed.

**Diagnostic:** approvals bottlenecking → delegate authority to defined value thresholds rather
than escalating faster `→ Table 3-1, p. 112`.

---

## MOMENT 4 — Ending

### Close Project or Phase (Closing)
**The only Closing process in the entire standard.** Everything about ending folds in here.

1. Acceptance confirmed and recorded (Validate Scope evidence → `05-scope.md`)
2. Contracts and procurements closed, claims settled `→ X4.9, p. 252`
3. Resources released — and released *well*; this is a leadership act with reputational
   consequences for the PM
4. Knowledge consolidated into organisational repositories `→ Standard §2.2.4, p. 21`
5. Financial closure and final variance position
6. **Benefits handover: who owns realisation after the project ends, and when it is measured**
7. Formal authorisation to close, mirroring the authorisation to start

Point 6 is where most closures fail. Projects deliver outputs and dissolve; benefits appear
months later with nobody accountable. Name the owner and the measurement date in the closure
record, or the value case was theatre.

Phase closure uses the same process at each gate.

---

## Tailoring — §2.1.7, p. 33
Calibrate on: regulatory and audit exposure · organisational governance maturity · project
value and visibility · number of external parties · predictive vs adaptive · delegated
authority available.

Structured vs self-governed is a spectrum `→ Figure 2-1, p. 12`. High-autonomy teams need
decision rights written down **more**, not less — there is no hierarchy to fall back on when
it is ambiguous.

## Interactions — §2.1.8, p. 35 (Table 2-4, p. 36)
The book notes Scope–Governance as often the most important interaction, since scope is where
the project's core value sits. Hot edges in practice:
- **→ Finance:** authorisation limits, funding gates, reserve release authority
- **→ Scope:** change disposition
- **→ Stakeholders:** who sits in which decision forum
- **→ Risk:** escalation thresholds

## Check outcomes — Table 2-5, p. 37 (restated)
1. **Appropriate oversight** — agreed processes, protocols and team agreements documented and
   aligned with organisational governance artifacts.
2. **Governance in place, effective, continuously improved** — teams aware of and acting on
   governance structure, audit/compliance and customer requirements; verified via compliance
   audits or checklists (predictive) or timeboxing and meeting cadence discipline (adaptive).
3. **Signalling mechanisms tied to target outcomes** — chosen to fit how *this* project
   maximises value.
4. **Lessons and retrospectives managed throughout** — not only at the end.
5. **Key management kept apprised** — metrics tracked regularly across the eleven-item list
   above.
