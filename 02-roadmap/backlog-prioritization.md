# Meridian Foundations — Backlog Prioritization

> Module 2 · Exercise 1: Audit and Prioritize Your Backlog
> Status: Exercise 1 decisions and peer feedback captured; Exercise 2 roadmap refinement is separate.

## Strategic context

Win photo-based site-issue coordination for field superintendents on existing US commercial projects worth $50M or more, with subcontractor foremen participating in resolution. Preserve enterprise functionality and build additively on Meridian's existing platform.

The commercial-project focus and selected workflow are strategic choices to validate, not measured research findings.

### M1 Objective and Key Results

**Objective:** Make Meridian Foundations the default way field superintendents on existing US commercial projects worth $50M or more coordinate site issues—without chasing group texts or entering the same update twice.

- **KR1 — Workflow adoption:** Increase eligible site issues coordinated end-to-end in Meridian from an assumed 10% to a proposed 60% by pilot week 12.
- **KR2 — Less chasing:** Reduce superintendent time spent chasing ownership and status updates from an assumed 60 to a proposed 30 minutes per workday by pilot week 12.
- **KR3 — No duplicate entry:** Increase field-captured issues available in the enterprise record without manual reentry from an assumed 20% to a proposed 90% by pilot week 12.

All numerical baselines are illustrative planning assumptions, not Meridian data. Targets are proposed and require validation. Eligible issues are routine, photo-documentable coordination issues, not emergencies or formal RFIs requiring separate procedures. KR1's denominator includes eligible issues handled outside Meridian.

[Full Module 1 strategy and OKRs](../01-strategy/strategy-and-okrs.md)

## Impact vs. Effort audit

Scores are provisional judgments, not measured impact or engineering estimates. Impact measures contribution to the specific M1 outcomes, not general commercial value: 1 = little direct contribution; 3 = supporting contribution; 5 = essential to the workflow. Effort covers engineering, design, and PM time for an additive pilot scope: 1 = small change; 3 = bounded cross-functional work; 5 = broad architectural/module work.

For this draft, high impact = 4–5 and lower effort = 1–3. Validate estimates with engineering and field research. Matrix categories inform decisions; strategic dependencies and service obligations can override them explicitly.

| # | Backlog item | Impact / 5 | Effort / 5 | Matrix position | Decision and rationale |
|---|---|---|---|---|---|
| 1 | Offline-first mobile experience | 5 | 4 | Plan Carefully | Rock: poor connectivity can break the core workflow. Stage a bounded issue-workflow pilot, not platform-wide offline support. |
| 2 | Photo markup and annotation | 4 | 2 | Do Now | Initial Rock: clearer context may reduce clarification and chasing. Peer challenged its Rock status; keep the hypothesis open. |
| 3 | Data-model migration for multi-project dashboards | 1 | 5 | Avoid | Hard No: a dashboard-led migration consumes capacity without directly improving the chosen field workflow. |
| 4 | Daily log: 14 required fields to 4 | 3 | 2 | Fill Gaps | Useful field improvement, but a separate workflow. Validate mandatory compliance fields before simplifying. |
| 5 | Automated compliance checklist generator | 2 | 4 | Avoid | Defer new automation; preserve existing compliance functionality. |
| 6 | Weather integration for scheduling | 2 | 2 | Fill Gaps | Helpful context, but not a prerequisite for issue capture, ownership, or resolution. |
| 7 | Foreman-facing mobile app | 5 | 3 | Do Now | Rock only as a narrow, additive issue-participation surface on existing services. A broad standalone app requires re-estimation. |
| 8 | Broken Procore import/export for 2 clients | 2 | 2 | Fill Gaps | Triage immediately as a service obligation; reserve bounded repair capacity if contract-critical or causing data loss. Not a new strategic Rock. |
| 9 | AI-assisted RFI drafting | 2 | 4 | Avoid | Formal RFI drafting is outside routine photo-based issue coordination and adds validation complexity. |
| 10 | Executive KPI dashboard; 2 renewals at risk | 1 | 3 | Avoid | Hard No: does not directly move field outcomes. Investigate renewal exposure before final resource commitment. |
| 11 | Push notifications for schedule changes | 3 | 2 | Fill Gaps | Schedule notifications are not issue-ownership notifications. Validate relevance before adding scope. |
| 12 | Time-tracking module | 1 | 5 | Avoid | Hard No: separate workflow driven by contract negotiations, not our selected adoption problem. |
| 13 | Web UI refresh | 1 | 3 | Avoid | Defer prospect-driven cosmetic work that does not remove the field workflow barrier. |
| 14 | Subcontractor document-sharing portal | 3 | 4 | Avoid | Defer this quarter; broad portal scope is not required for minimal foreman participation. Revisit if research establishes a dependency. |

### Reality check

The lab recommends halving impact and doubling effort estimates as a pessimism check. This would make the mobile work materially less attractive; it does not validate delivery feasibility. Re-estimate and constrain the pilot before commitment. Do not assume the 10-person team can deliver three full-sized initiatives concurrently.

Offline capability is promoted from Plan Carefully to a Rock because it is a strategic prerequisite, not because the matrix identifies it as a quick win.

## Three Rocks — Exercise 1 selections

### Rock #1: Item #1 — Offline-first mobile experience

Enable superintendents to capture and progress site issues despite poor connectivity, supporting **KR1** and **KR3**. Limit the pilot to the issue workflow and reliable synchronization, not full-platform offline coverage. High effort places it in Plan Carefully, but its prerequisite role warrants a strategic Rock.

### Rock #2: Item #2 — Photo markup and annotation

Let superintendents show exactly where and what the problem is so foremen need fewer clarification exchanges, supporting **KR2** and **KR1**. The effect on chasing is a hypothesis, not established evidence. This initial selection remains recorded here; its status is challenged by peer feedback below.

### Rock #3: Item #7 — Foreman-facing mobile app

Provide a narrow, additive mobile surface for foremen to receive assigned issues and confirm resolution against the same Meridian record, supporting **KR1**, **KR2**, and **KR3**. Reuse the enterprise backend; do not rebuild Meridian or create a broad standalone field platform. Validate scope and effort with engineering.

## Three Hard Nos — this quarter

### Hard No #1: Item #10 — Executive reporting dashboard with custom KPIs

We will not build new executive dashboards this quarter, despite two renewals being at risk, because doing so would divert the team from field adoption; sales and customer success must quantify exposure and test existing reporting workarounds, with material business risk triggering an explicit strategy review.

### Hard No #2: Item #12 — Time-tracking module

We will not add a time-tracking module this quarter because three contract negotiations do not justify opening a separate workflow before the issue-coordination adoption bet is proven.

### Hard No #3: Item #3 — Data-model migration for multi-project dashboards

We will not fund a dashboard-driven migration this quarter because it advances the enterprise analytics expansion excluded in M1 rather than the selected field workflow; if engineering demonstrates a dependency for the Rocks, reassess only the minimum enabling change.

## Peer review — Show and Swap

### Do the Rock selections feel traceable to a clear strategy, or do they read like a feature list?

My peer considers Rock #1 (offline-first mobile) and Rock #3 (foreman-facing mobile app) solid. He sees Rock #2 (photo markup and annotation) as a Pebble: an enhancement rather than a game-changing strategic capability.

### Pick one Hard No and make the case for why it should actually be a Rock.

My peer challenged Hard No #3 (data-model migration for multi-project dashboards): the current effort estimate is high, but AI could reduce implementation cost and effort enough to warrant reconsidering the decision.

## Response and open decisions for Exercise 2

- **Photo markup:** Fair challenge. It supports the workflow, but we have not shown that annotation is essential to reducing coordination effort. Reconsider its independent Rock status rather than defending it simply because it was selected. No replacement Rock has been agreed.
- **AI-assisted migration:** Revisit the effort estimate if credible evidence supports a reduction. Lower implementation cost alone does not establish strategic value. Reconsider the migration if it enables the field Rocks or the strategy changes.

These are responses to peer feedback, not additional comments attributed to the peer. Preserve the Exercise 1 selections as the review baseline; record any subsequent changes in the roadmap and trade-off memo.
