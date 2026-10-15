# Outcome Roadmap & Trade-off Memo: Meridian Foundations

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2

## 1. Outcome roadmap

**Objective:** Make Meridian Foundations the default way field superintendents on existing US commercial projects worth $50M or more coordinate site issues—without chasing group texts or entering the same update twice.

**Scope:** Routine, photo-documentable site issues, with subcontractor foremen participating in resolution. Foundations is additive to Meridian's enterprise platform; existing finance and compliance functionality remains intact.

**Success measures:** KR1: end-to-end eligible issue adoption, assumed 10% → proposed 60%. KR2: superintendent time chasing ownership and status, assumed 60 → proposed 30 minutes per workday. KR3: field-captured issues available in the enterprise record without manual reentry, assumed 20% → proposed 90%. Proposed evaluation deadline: end of pilot week 12.

The scenario provides no quantitative workflow baselines. These baselines are illustrative assumptions, and targets require validation. KR1 includes eligible issues handled outside Meridian, not only those entered into the app. Proposed owners are functional responsibilities within the scenario, not confirmed staffing assignments.

Horizon ranges are planning bands relative to initiative start, not delivery-date promises. Now defines the proposed quarter focus; Next and Later are conditional on pilot evidence, dependencies, and capacity. Later items are exploratory hypotheses, not validated demand.

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | We bet offline issue capture and reliable synchronization will increase end-to-end issue adoption and eliminate manual reentry for field superintendents on existing US commercial job sites. | Mobile engineering, product, UX research, customer success | KR1 and KR3; verify captured issues survive connectivity loss and reach the enterprise record without manual reentry. |
| Now (0 to 3 mo) | We bet a minimal mobile workflow for foremen to receive assigned issues and confirm resolution will reduce superintendent time chasing updates and increase end-to-end issue adoption. | Product, mobile engineering, UX research, customer success | KR2 and KR1; observe whether foremen participate without additional superintendent chasing. |
| Next (3 to 6 mo) | More participating foremen complete the issue workflow without onboarding assistance. Sequence targeted onboarding improvements after the pilot identifies actual participation barriers. | UX research, product, customer success, mobile engineering | Better unaided completion and sustained end-to-end participation supporting KR1; set targets after measuring the pilot baseline. |
| Next (3 to 6 mo) | Field teams spend less effort completing required daily logs. Evaluate backlog #4 only after issue coordination demonstrates value and required compliance data can be preserved. | Product, UX research, engineering, customer success | Lower daily-log completion effort with required records preserved; separate baseline needed because daily reporting extends beyond the current issue-workflow KRs. |
| Next (3 to 6 mo) | Superintendents spend less effort chasing coordination updates affected by schedule changes. Test backlog #11 only if research connects schedule-change notifications to that effort. | Product, mobile engineering, UX research | Reduced coordination chasing supporting KR2, without excessive or irrelevant notifications; no delivery commitment before relevance is established. |
| Later (6 to 12 mo) | Bet: subcontractors access relevant documents without asking office teams. Explore a narrow version of backlog #14 only if missing documents repeatedly block issue resolution. | Product, engineering, UX research, customer success | Evidence that document access is a recurring blocker, followed by reduced document-related chasing; feasibility and demand remain unvalidated. |
| Later (6 to 12 mo) | Bet: mid-market contractors adopt the proven field workflow without enterprise-heavy onboarding. Expansion follows field value in existing accounts, not the reverse. | Product, UX research, customer success | Evidence of repeat field use and lower coordination effort in the initial segment, followed by segment-specific adoption and commercial validation. |

## 2. Trade-off memo

### What I sequence first

I sequence reliable field capture and accountable handoff first because both are necessary for the chosen job: capture an issue once, get it to the responsible person, and know it is resolved without chasing or reentry. Offline capability is high-effort but is an enabling dependency, not optional polish. The foreman surface reuses the existing enterprise backend rather than rebuilding Meridian.

These two bets draw on Exercise 1 Rocks #1 and #3. They form one bounded pilot workflow, not two unrelated platform initiatives. Establish enterprise record and synchronization behavior before expanding the participating foreman cohort. Re-estimate the combined scope with engineering before committing resources; the scenario's 10-person team is not evidence of sufficient capacity for full-sized implementations.

### What I change after peer review

My peer judged offline-first and the foreman-facing app solid, but considered photo markup a Pebble. I accept that annotation has not earned an independent strategic commitment. Exercise 1's three original selections remain documented, but this roadmap has two Now bets rather than inventing a third.

Photo clarity supports the core workflow. Test whether a photo and short description already communicate enough to act; add minimal annotation only if observation shows ambiguity materially contributes to chasing and if it fits the pilot capacity. It is supporting work, not a separate Now initiative or a guaranteed feature.

### What I push out

I push daily-log simplification, schedule-change notifications, broad document sharing, and mid-market expansion out of the initial scope. Daily logging is a separate workflow; schedule-change notifications are not issue notifications; broad document sharing is not required for minimal issue participation. Each needs its own evidence or dependency case before receiving capacity. Mid-market expansion remains secondary to proving field adoption.

I also defer new compliance automation, weather integration, AI-assisted formal RFI drafting, and cosmetic web UI refresh this quarter. Existing compliance functionality stays intact; formal RFIs and emergencies remain outside the routine issue workflow.

### What I exclude this quarter

- **Executive reporting dashboard (#10):** It does not directly advance the selected field outcomes and conflicts with M1's exclusion of advanced enterprise analytics. Two renewals are at risk, so customer success and sales must quantify exposure and test existing reporting workarounds. If verified exposure threatens the initiative's viability, reopen the strategic decision explicitly rather than quietly add dashboard scope.
- **Time-tracking module (#12):** Three contract negotiations do not establish that a separate time-tracking workflow will solve field issue adoption. Assess the opportunity cost, but do not expand the initiative around a sales-led module.
- **Dashboard-driven data-model migration (#3):** A cheaper migration is not automatically a more valuable field bet. My peer's AI-efficiency challenge warrants testing the effort estimate, including review, testing, and rollout costs. Reconsider only the minimum enabling change if engineering demonstrates that the field workflow depends on it; do not authorize the dashboard-led migration solely because coding costs fall.

These are exclusions for this quarter and initiative, not claims that the opportunities should never be pursued.

### Service obligations and cost of delay

Triage the broken Procore integration (#8) immediately as an existing-customer service obligation. Reserve bounded repair capacity if it is contract-critical or causing data loss; do not disguise defect repair as a new strategic Rock.

Delaying reliable capture or foreman participation delays the entire adoption experiment. Delaying office dashboards may incur renewal risk, while adding them now delays field validation. The decision is to prioritize the field workflow while actively investigating commercial exposure and protecting existing service obligations.

I do not calculate WSJF scores or monetary cost of delay: the scenario lacks credible duration, revenue exposure, and delay-cost estimates. Fabricated precision would weaken the decision. Use those estimates when available to review sequencing, not to replace strategic alignment.

### Review and accountability

Product owns the roadmap and reviews it with engineering, UX research, and customer success at each sprint review. Track the M1 outcomes weekly and assess coordination effort and enterprise guardrails monthly. Expand only when repeat field use and reduced coordination effort improve together.

Revisit priorities if foremen do not participate, synchronization cannot preserve required records, pilot evidence does not show less chasing, or verified renewal exposure materially changes the business trade-off. Revise targets after validating baselines; do not treat mandated app use as proof of user value.

[Exercise 1 audit, original priorities, and peer feedback](./backlog-prioritization.md)
