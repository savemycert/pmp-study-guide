# Domain 3: Business Environment (26%)

This domain connects the project to the organization around it: governance, compliance, change control, impediments and issues, risk, continuous improvement, organizational change and the external environment. Questions are situational and turn on who holds the authority to decide, whether something is uncertain (a risk) or has already happened (an issue), and whether the agreed route (change control, the product owner, the escalation path, the contract) is being followed or bypassed.

## 3.1 Define and establish project governance

- **Governance** decides who decides what, who oversees the work, and what the PM may decide alone. **Project management** plans and delivers inside it. Test: "who has authority to approve this, and who checks on us?" is governance.
- **Three enablers:** establish structure, rules, procedures, reporting, ethics and policies using OPAs; define success metrics; outline escalation paths and thresholds.

|                       | Organizational process assets (OPAs)                                                   | Enterprise environmental factors (EEFs)                                       |
| --------------------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| What                  | Assets the organization owns and the project can use and update                        | Conditions the project works within                                           |
| Examples              | Approval procedures, templates, gate checklists, lessons learned, historical estimates | Culture, risk appetite, structure, IT infrastructure, laws, market conditions |
| Project updates them? | Yes                                                                                    | No, only responds                                                             |

- Start governance from the approved OPAs and tailor them; do not build from scratch.
- **Roles:** sponsor (business case, funding, first escalation point), steering committee (decisions beyond individual authority, cross-unit conflicts), PMO (standards; does not own a project's business case), product owner (backlog within governance boundaries), gate or review boards.
- **Decision rights:** one accountable owner per decision type (a RACI helps). If someone acts outside their rights, point back to the agreement first; escalate only if it continues. Multi-unit, visible projects suit a steering committee rather than several sponsors.

| PMO type    | Control  | Signal                                                      |
| ----------- | -------- | ----------------------------------------------------------- |
| Supportive  | Low      | Templates and advice on request; use optional               |
| Controlling | Moderate | Requires compliance with its frameworks and audits it       |
| Directive   | High     | Manages projects; PMs are assigned by and report to the PMO |

- **Success metrics:** defined in initiation with stakeholders, traced to the business case, measuring **outcomes** (waiting time) not outputs (modules deployed), against this organization's own measured **baseline**, specific and agreed.
- **Thresholds (tolerances):** inside → act and record. **Forecast** breach → escalate now, with cause, options and a recommendation. Do not take an above-threshold decision unilaterally. Contingency is the PM's (inside the baseline); management reserve is released by management, never self-funded.
- **Escalation paths:** a decision owner at each level, response times, named alternates, the right first forum. Follow it in order.
- **Governance reporting:** by exception, decision-framed, forward-looking (a known upcoming problem changes status now, even with healthy indices), empirical forecasts from velocity for agile work, truthful. Change a mandated report through the tailoring route (often PMO approval).
- **Phase gates:** go, conditional go, rework or hold, stop. The gate sees the updated business case, not just a deliverables checklist. Agile governance uses **guardrails with exception review** and impact thresholds on date, budget and release goal.
- **Ethics:** disclose a conflict of interest and step aside; decline gifts above the policy limit; discuss pressure to misreport with the requester, then report the true status.
- **Tailoring:** propose the level of governance through the route the guidelines name. Hybrid: baseline change control for regulated workstreams, delegated decisions for agile ones, one oversight body.

**Traps**

- Culture and risk appetite are internal but are EEFs, not OPAs.
- "Requires standards" fits both controlling and directive PMOs; ask whether it also manages the PMs.

📖 Full lesson: [PMP Project Governance: Decision Rights, Escalation Thresholds and Success Metrics](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-project-governance-escalation-success-metrics/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.2 Plan and manage project compliance

- **Seven enablers:** confirm requirements, classify categories, determine threats, use methods to support compliance, analyze consequences of noncompliance, determine the approach and actions, measure the extent of compliance.
- **Confirm early with qualified experts** (legal, compliance, safety, privacy, environmental) for this work, site and jurisdiction. Earlier lists, the sponsor's view or the team's own reading are inputs only. Re-confirm when scope adds a market, site, customer group or data type. In agile work, confirmed requirements become backlog items, acceptance criteria and definition-of-done conditions.

| Category            | Who can change it                                                |
| ------------------- | ---------------------------------------------------------------- |
| Regulatory or legal | Only the authority that sets or issues it                        |
| Contractual         | Only the parties, by agreeing a contract change                  |
| Internal policy     | The organization, through its governance/tailoring               |
| Voluntary standard  | The adopting organization, unless it became contractual or legal |

- A voluntary standard written into a contract is binding. A contractual clause is not a law. A law binds whether or not the contract repeats it.
- **Threats to compliance** (risk register): pending rule changes, unassessed suppliers, new tools (a security certificate says nothing about data residency), schedule recovery that breaks a permit's conditions, shortcut pressure. A gap that has already happened is an **issue**.
- **Methods:** train before new procedures (prevention before detection); check daily obligations daily; build controls into the workflow; one owner per obligation; audits; a compliance register.
- **Agile compliance:** compliance impact assessment in refinement, automated checks and evidence in the pipeline, mandatory steps in the definition of done.
- **Compliance register:** obligation → control → owner → evidence. Used for audits, change impact analysis when a rule changes, and handover to operations as a living record.
- **Consequences of noncompliance:** fines, stop orders, harm, liability, loss of licences, rework, reputation. Never trade a mandatory requirement on expected value. A change control board cannot waive a law. Protect people first; containment and permanent repair can be separate steps.
- **Responding to a gap:** contain the harm (proportionately) → inform compliance owners through governance → analyze and correct the cause (root cause plus dated corrective actions) → update plans through change control and log the issue.
- **Honesty:** never attest to unverified controls; report open items with owner and date; falsified records need both a governance integrity response and new independent evidence.
- **Suppliers:** put obligations in the contract, get evidence through audits, remember accountability to the regulator cannot be transferred by indemnity.
- **Measure** with verified evidence (share of obligations with current evidence, control test results, overdue corrective actions), not activity.

**Traps**

- A requested permit variation is not a granted one.
- Extra precautions do not change what an obligation allows.

📖 Full lesson: [PMP Project Compliance Management: Requirements, Threats, Evidence and Noncompliance](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-project-compliance-management/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.3 Manage and control changes

- **Four enablers:** execute the change control process, communicate change status, implement approved changes, update documentation. The rules live in the **change management plan**.
- **Predictive sequence:** document → analyze → decide → communicate → implement → verify → update.
- **Capture every change request,** including hallway and chat requests. The PM can write it up for the requester. Do not act first; seniority and funding do not bypass the process; urgency changes the speed, not the authority. Changes go in the **change log**, not the issue log.
- **Integrated impact analysis** covers scope, schedule, cost, quality, resources, risk, contracts, compliance and other streams, with options. "No change to the end date" achieved by crashing or fast tracking still has cost or risk impact.

| Situation                               | Decides                                             |
| --------------------------------------- | --------------------------------------------------- |
| Within every delegated limit            | Project manager (record it)                         |
| Breaches any one limit                  | Next authority, usually the CCB                     |
| Beyond the board's authority            | Sponsor or governance body                          |
| Product scope inside the team's backlog | Product owner                                       |
| A contract                              | Contracting authority, via the contract's procedure |

- **Agile:** change goes into the product backlog; the product owner orders it. Under the Scrum Guide (2020), no changes that endanger the sprint goal; only the product owner may cancel a sprint.
- **Hybrid routing:** story-level change inside a committed feature → backlog. Contracted or baselined date, scope or milestone → change request (even if the product owner agrees). Spend above the cost baseline → change request. Vendor work → contract procedure.
- **Emergency change:** only when the plan's criteria are met; the named person approves; document and review afterwards; covers only the emergency.
- **Unauthorized change** discovered later: document it, assess it with qualified people, let the right authority accept, rework or reverse.

| Change request type | Purpose                                |
| ------------------- | -------------------------------------- |
| Corrective action   | Bring current performance back to plan |
| Preventive action   | Keep future performance on plan        |
| Defect repair       | Fix a nonconforming product            |
| Update              | Change controlled documents or plans   |

- **Communicate status** through a visible change log, including rejections with reasons; announce approvals when made. Agile: a visible backlog and sprint reviews.
- **Implement exactly as approved** (conditions included); if it outgrows the plan's limits, return it for a decision; verify before closing the log entry.
- **Contracts:** CCB approval changes the project plan, not the contract; procurement amends the contract. Seller claims go through the contract's change procedure.
- **Update** every artifact the impact analysis lists, and nothing it does not.
- **Configuration management:** identification, status accounting, verification and audit (PMI); version control puts configuration control into practice. Parties working from different versions is a configuration problem.

**Traps**

- A complete request form is not an analyzed request.
- Formal control on story-level detail adds delay; backlog approval of a contracted commitment bypasses control.

📖 Full lesson: [PMP Integrated Change Control: Change Requests, CCB, Agile Change and Configuration Management](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-integrated-change-control-process/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.4 Remove impediments and manage issues

- An **impediment** (blocker) is anything that stops or slows the team; an **issue** is a current condition affecting objectives. Agile teams say impediment, predictive teams say issue.
- **Cycle:** evaluate impact → prioritize and highlight → apply an intervention → reassess until the work moves. Plus: recognize when a risk becomes an issue, and resolve issues with the relevant stakeholders.
- **Evaluate first:** what does it block, for how long, does it threaten the sprint goal, a committed release or the critical path, and does float absorb it?
  - A 6-day slip on an activity with 2 days of float moves the end date by 4 days (more than a 3-day critical-path slip).
  - Parallel path delays feeding one milestone do not add up: the milestone moves by the largest net delay (delay minus float).
- **Prioritize** by effect on the goal, commitments and value, not by age, noise or who raised it. A **Pareto chart** of logged impediments shows the vital few categories.
- **Highlight** to whoever can clear it, while there is time: impediment board, information radiators, the daily stand-up, a shared prioritized list for managers outside the team.

| Situation                                       | Intervention                                                        |
| ----------------------------------------------- | ------------------------------------------------------------------- |
| Blocker outside the team                        | PM removes it with the owning group and shields the team            |
| Within the team's capability                    | Coach and facilitate; the team agrees its own fix                   |
| Cannot be removed in time                       | Minimize: resequence, swarm, tailor the slow process with its owner |
| Beyond the PM's authority after direct attempts | Escalate through governance with impact and options                 |

- **Shield by channelling:** route ad hoc stakeholder requests through the product owner. A stuck team-owned decision → raise facilitation (for example a time-boxed spike), not decide for them.
- **Required controls** (regulatory approval, review board) are never bypassed. Reorder work, agree a faster route with the control's owner, or use its own rules (a named deputy approver).
- **Escalate** only after collaborating with the impediment's owner, to the decision-maker the governance plan names, with impact and options. Handle slips within your threshold directly.
- **Reassess:** resolved means the work is moving. Recurring blockers need root-cause work with the system's owners.
- **Risk becomes issue** when the event happens or is certain. Triggers, higher probability or more worry leave it a risk.
  - Identified risk occurs → risk owner runs the planned response, funded from **contingency**; log the issue; mark the register entry as occurred.
  - Unidentified problem → **workaround** with those affected; funding from **management reserve** with sponsor/management approval, which adds to the cost baseline through change control.
- **Issue log:** description, owner, target date, status, resolution. An issue with no owner or date is not managed. Resolve cross-boundary issues with the parties who own part of it; agile defects competing with sprint work go to the product owner.

**Traps**

- An old, unanswered blocker is not more urgent just because it is old.
- Releasing first and informing the control owner afterwards is a bypass.

📖 Full lesson: [PMP Impediments and Issues: Remove Blockers, Escalate and Resolve](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-remove-impediments-manage-issues/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.5 Plan and manage risk

- A **risk** is an uncertain event or condition with a positive (**opportunity**) or negative (**threat**) effect. **Individual** risks live in the register; **overall project risk** is the combined effect of all uncertainty and can be high when no single risk is.
- **Seven enablers:** develop the plan, identify, analyze, maintain the register (ECO example: poor IT security), execute the plan (security and sustainability examples), monitor and control, communicate status.
- **Risk management plan** (approach): methodology, roles, funding, timing, categories (risk breakdown structure), probability and impact scales and matrix, appetite and thresholds, reporting. **Risk register** (each risk): statement, owner, ratings, triggers, responses, contingency and fallback, residual and secondary risks, status, watch list. Tailor the plan's size to the project.
- **Appetite → thresholds.** A zero-tolerance threshold overrides a low matrix score. A missed overall confidence threshold calls for responses to overall risk, agreed with the sponsor.
- **Identify** early, with the team, continuously: brainstorming, expert interviews, assumption and constraint analysis, checklists, prompt lists (PESTLE, RBS), root cause analysis, SWOT.
- **Risk statement:** "Because of cause, event may occur, which would lead to effect." Something that has happened is an issue; a certain fact (a published rule) can be the cause of new risks.
- **Qualitative analysis** for every risk: probability × impact on the plan's scales, plus urgency and manageability. Check **risk data quality** before acting. Low risks go on the **watch list**, not deleted.
- **Quantitative analysis** where warranted: Monte Carlo → S-curve (how likely to hit the date or budget overall); sensitivity analysis → tornado diagram (which uncertainties drive it); decision tree (which option under uncertainty). A single-path PERT probability is optimistic (merge bias).

| Threat   | Does                                              | Opportunity | Does                                              |
| -------- | ------------------------------------------------- | ----------- | ------------------------------------------------- |
| Escalate | Pass to program/portfolio/business owner          | Escalate    | Same                                              |
| Avoid    | Remove the threat entirely                        | Exploit     | Make the opportunity certain                      |
| Transfer | Shift the consequence to a third party            | Share       | Give part of the benefit to a better-placed party |
| Mitigate | Reduce probability or impact                      | Enhance     | Increase probability or impact                    |
| Accept   | Active (contingency plan with trigger) or passive | Accept      | Take it if it arrives                             |

- Transfer never removes the threat (and creates a secondary risk that the other party fails). Only exploit makes an opportunity certain.
- **Escalate** risks whose cause or response is outside the project's scope or authority. Once the receiving owner accepts, mark the entry escalated and stop monitoring it.
- **Execution vocabulary:** risk owner (a named person, not "the team"), trigger, contingency plan (run when the trigger fires), fallback plan (if the contingency fails), workaround (unplanned response to an unidentified or passively accepted risk that occurred). Contingency spending per the plan needs no CCB, but follows any approval rule the plan sets.
- **Residual risk** remains after a response; **secondary risk** is created by a response and gets its own response.
- **Register entries must be specific:** "poor IT security" is a label; name the cause, event, owner, trigger and actions.
- **Risk review** asks whether the register is right (re-rate, close, add). **Risk audit** asks whether the process works (owners know their risks, responses are ready).
- **Agile:** risk-adjusted backlog, spikes, risk raised in every event, risk boards and burndowns, frequent increments as a response. Hybrid: formal register for predictive parts, backlog for adaptive parts, one view.
- **Security:** an unmasked-data plan not yet executed is a risk; zero tolerance rules out acceptance and transfer; prefer the narrowest effective avoidance. **Sustainability:** consider the product's whole operating life; mitigate through design while it is still open.
- **Communicate** overall exposure, trend, impact on objectives and decisions needed to sponsors; detail to the team; timing follows the risk, not the calendar.

**Traps**

- Insurance pays for a breach; it does not prevent one.
- A probability and impact matrix prioritizes; it does not identify risks.

📖 Full lesson: [PMP Risk Management: Plan, Register, Analysis and Responses](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-risk-management-plan-register-responses/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.6 Continuous improvement

- **Three enablers:** utilize lessons learned, help ensure continuous improvement processes are updated, update organizational process assets. Learning only counts when it changes something, and improvement follows the agreed route.
- **OPA vs EEF:** classify by what it is. A documented procedure is an OPA even if disliked; senior managers' attitudes are an EEF though internal. Own historical records are OPAs; purchased industry data is an EEF. A change in an EEF (a new law) often triggers an OPA update through its owner.
- **Before the baseline:** review lessons and historical data from similar work; let evidence override an unsupported estimate; turn past problems into early-acting risk responses.
- **Lessons learned register** is updated whenever a lesson emerges (retrospectives included), tagged for reuse, and moves to the organizational repository at phase or project end.

| Record                   | Holds                                            |
| ------------------------ | ------------------------------------------------ |
| Lessons learned register | What happened, why, what to do differently       |
| Issue log                | Current problems needing an owner and resolution |
| Risk register            | Uncertain future events and responses            |
| Change log               | Change requests and decisions                    |

- **A usable lesson:** what happened, impact, verified root cause, recommendation, in neutral language. Record good practice too.
- **Apply lessons now** to the remaining work (next phase, remaining releases). Anything that changes a baseline goes through change control with the evidence.
- **Retrospective actions** become owned backlog items; pick one or two; take constraints owned outside the team to their owner and follow up.
- **Organizational processes** change through their owners. Propose with evidence, keep complying until approved, treat a "no" as information. Tailor within allowed limits and record why; repeated identical tailoring is evidence the standard should change.
- **PDCA:** pilot, check measured results, then act. Clear win → ask the process owner to standardize. Mixed result → analyze the trade-off. Different context → test before adopting there.

| Approach                       | Recognize it by                                             |
| ------------------------------ | ----------------------------------------------------------- |
| Kaizen                         | Steady small steps from everyone, especially the front line |
| PDCA                           | Pilot, compare with prediction, then adopt or revise        |
| Six Sigma (DMAIC)              | Data-driven reduction of variation and defects              |
| Lean value stream mapping      | Seeing where work waits between steps                       |
| Business process reengineering | One radical redesign from scratch                           |

- **Update OPAs:** historical estimating data (with context notes for unusual conditions), risk checklists and templates through their owners. Make the repository searchable. A defect in a shared asset → warn current users now and report it to the owner.

**Traps**

- Logging a risk against an estimate known to be unrealistic does not make the estimate acceptable.
- A senior person who does not own a policy cannot approve a change to it.

📖 Full lesson: [PMP Continuous Improvement: Lessons Learned, Process Updates and Organizational Process Assets](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-continuous-improvement-lessons-learned-opas/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.7 Support organizational change

- **Two enablers:** assess organizational culture; evaluate the impact of organizational change on the project and determine required actions. Projects both deliver organizational change and are exposed to it.
- **Assess culture from evidence:** observation of real decisions, interviews, repeated patterns in lessons learned (plan around them), behavioural signals (silent retrospectives, status green until a milestone is missed), surveys for breadth only.
- **Espoused vs enacted culture:** when stated values and behaviour disagree, believe the behaviour. Culture is an **EEF**: discover it, plan around it, move it gradually.

| Cultural factor       | Project adapts by                                                                 |
| --------------------- | --------------------------------------------------------------------------------- |
| Risk appetite         | Setting thresholds and release decisions per unit                                 |
| Hierarchy / deference | Growing autonomy in steps; gathering candid input where people feel free to speak |
| Blame vs safety       | Making bad news safe and valued; more pressure treats only the symptom            |
| Decision-making style | Doing informal groundwork with each group before the formal forum                 |

- **Subcultures:** assess a distinct unit on its own rather than trusting a group-level average. After a merger, first make both groups' norms and their reasons visible; aim for a **minimum common framework plus local tailoring**, agreed with the PMO.
- **Agile suitability filter** (Agile Practice Guide) scores culture, team and project. A strong project score does not override a weak culture score; a mixed result usually means hybrid plus actions agreed with the sponsor. Renaming practices without changing controls is not tailoring.
- **Evaluate an organizational change before acting:** strategic fit, authority, stakeholders, resources, ways of working, people. Announced but undecided → map exposure now and keep delivering. Hiring freeze → quantify and take options through governance. New funding policy → work out its effect before the first decision point.
- **Sponsor change:** engage a new sponsor early and in person on the vision and business case. A leader questioning value needs the business case and benefits, not SPI and CPI. No successor → ask the appointing body to name one formally; act only through people who hold the authority.
- **Strategy shift:** reassess value with the sponsor and product owner; bring continue, adapt and stop options to governance, who decide.
- **Reorganization:** re-agree capacity with the new resource owner; update the RACI, resource plan, stakeholder register and decision bodies. Documents recording **what** the project delivers change only if the work changes.

| Model            | Stages                                                                                                                 | Use it to                                      |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| Kotter (8 steps) | Urgency, guiding coalition, vision, communicate, remove obstacles, short-term wins, build on change, anchor in culture | Plan how leaders drive the change              |
| ADKAR            | Awareness, Desire, Knowledge, Ability, Reinforcement                                                                   | Find the first missing element (barrier point) |
| Bridges          | Ending, neutral zone, new beginning                                                                                    | Support the emotional transition               |
| Satir            | Late status quo, foreign element, chaos, transforming idea, practice and integration, new status quo                   | Explain the temporary performance dip          |

- **ADKAR Knowledge vs Ability:** trained and can explain the steps vs can actually do it under real conditions. Ability comes from coaching and practice, not more explanation.
- **Satir:** a dip with sound outcome measures and an upward trend is expected; explain it and keep support. A dip with worsening outcomes needs investigation.
- **Resistance is information:** ask and observe first, then fix design, timing, workload or skills. **Readiness assessments:** act on the specific gap.
- **Team uncertainty:** share what is known and unknown, never promise what you do not control, keep confidences without misleading, raise announcement timing with its owner.

**Traps**

- Using senior authority to order people to be candid reinforces the hierarchy problem.
- Continuing, adapting or cancelling is a governance decision, even when one option looks cheaper.

📖 Full lesson: [PMP Organizational Change: Assessing Culture and Responding to Change](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-organizational-change-and-culture/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 3.8 Evaluate external business environment changes

- **Three enablers:** survey external changes (regulations, technology, geopolitical, market); assess and prioritize the impact on scope or backlog; continually review the environment.
- **External vs internal:** a law, competitor move, vendor retirement, sanctions, exchange rates or customer behaviour shift is external. A reorganization, resignation, new PMO template or sponsor change is internal (handled under other tasks).

| PESTLE        | Examples                                                         |
| ------------- | ---------------------------------------------------------------- |
| Political     | Trade policy, sanctions, subsidies, elections                    |
| Economic      | Inflation, interest and exchange rates, energy prices            |
| Social        | Attitudes, habits, preferences, demographics                     |
| Technological | New services, end-of-support dates, security threats             |
| Legal         | Laws, regulations, standards, licensing                          |
| Environmental | Climate events, waste and recycling rules, environmental permits |

- Classify by the kind of thing that changed: a change in preferences is **Social**, whatever it is about.
- **Feed the scan** from the experts who already watch each area (legal, trade compliance, procurement, finance, product marketing, customer research). Validate second-hand signals against evidence.
- **Continual review:** build it into refinement and iteration reviews (agile) or risk reviews, status reviews and phase gates (predictive). Every watch item has an owner and review date; evolving changes have triggers (draft published, comment period closed, effective date set).
- **Assess before acting:** confirm facts, trace the effect across scope, contracts, cost, schedule, quality and benefits, size the reaction to what is actually affected, keep delivering meanwhile.

|             | Proposed / uncertain                    | Enacted / dated                           |
| ----------- | --------------------------------------- | ----------------------------------------- |
| Nature      | Risk                                    | Issue or requirement                      |
| Recorded in | Risk register / watch list              | Issue log, backlog, change request        |
| Handling    | Analyze, respond, set triggers, monitor | Assess impact, change the plan or backlog |

- **Keep options open cheaply:** isolate what a likely change would affect behind a swappable boundary, finish once the change is final.
- **A watched risk occurs:** run the planned response, funded from contingency; management reserve is for unknown-unknowns.
- **Regulation:** experts translate the rule into testable work; scope it to the markets it covers; the effective date is a deadline; predictive baselines still need a change request; in agile, make the date and consequence visible to the product owner, who reprioritizes.
- **Technology:** new and uncertain → time-boxed spike; retirement with a date → size and sequence the migration.
- **Geopolitical:** confirm the legal reach with legal or trade-compliance experts first; compliance cannot be delegated to a supplier. Hybrid supply disruption: predictive stream works the supply problem while the agile stream resequences dependent work.
- **Market:** validate the signal; the product owner reorders the backlog. With a fixed date and sustainable pace, scope is the variable.
- **Prioritize** by certainty, impact and urgency. Certain changes are handled now; uncertain severe ones get risk treatment. Sequence competing backlog items by **cost of delay** (WSJF divides it by job size).

| Impact touches                    | Route                           | Decides                  |
| --------------------------------- | ------------------------------- | ------------------------ |
| Predictive baseline or contract   | Change request                  | Change control board     |
| Agile backlog                     | Refinement and reprioritization | Product owner            |
| Hybrid                            | Split each part to its route    | CCB and product owner    |
| Expected benefits / business case | Business case review            | Sponsor, with governance |

- **Business case hit:** on-track metrics do not prove value; past approval is not current justification; ignore sunk cost; terminating or rescoping is legitimate; bring it to the sponsor now (a PMO advises but does not own the justification).

**Traps**

- A retirement date is a deadline to plan for, not a risk to monitor.
- Absorbing new mandatory work by stretching the team hides the trade-off.

📖 Full lesson: [PMP External Business Environment: Surveying and Assessing Outside Changes](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-external-business-environment-changes/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

[← Back to the study guide](../README.md)
