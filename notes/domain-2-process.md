# Domain 2: Process (41%)

This is the largest domain: integrated planning and the delivery approach, scope, value, resources, procurement, finance, quality, schedule, status and closure. Questions mix situational judgement with short calculations (PERT, effort to duration, WSJF, EMV, contract incentives, earned value, critical path and float). The deciding fact is usually in the stem: whether a baseline is approved, whether the work sits in a backlog or under change control, which constraint is fixed, and who holds the authority to decide.

## 2.1 Develop an integrated project management plan and plan delivery

- **Integrated plan** = subsidiary management plans + baselines + the delivery approach, made to fit together. The PM's job is that the pieces fit, not just that each exists.
- **Magnitude vs complexity:** magnitude is size (budget, sites, duration) and calls for decomposition and coordination. Complexity is uncertainty (unclear requirements, new technology, interdependencies, conflicting stakeholders) and calls for short feedback loops and re-planning. A huge road resurfacing job can be routine; a tiny integration proof of concept can be complex.
- **Approach is driven by** requirements uncertainty and technical uncertainty, plus how often the customer needs usable output.

| Life cycle  | Requirements             | Delivery           |
| ----------- | ------------------------ | ------------------ |
| Predictive  | Fixed up front           | Once, at the end   |
| Iterative   | Refined through feedback | Once               |
| Incremental | Stable enough per piece  | Frequent pieces    |
| Agile       | Dynamic                  | Frequent and small |

- **Hybrid:** predictive for well-defined components, adaptive for uncertain ones, integrated through dated milestones, capacity-based cost baselines (cost per iteration × iterations) and shared governance. Tailor per component, even mid-project. Record it in the plan's development approach component.
- **Critical information requirements** (sustainability is the ECO's example): define each item's definition, source, owner and cadence during planning. A known reporting obligation is a requirement, not a risk. Fix comparability at the source.
- **Execution strategy:** big bang, phased waves, pilot then rollout, or parallel running. The binding constraints eliminate options. You can separate preparation (in waves) from cutover (one date). Protect deadline-bound work that shares scarce specialists first.
- **Plan vs documents:**

| Project management plan (change control)                                                                                    | Project documents (updated as work proceeds)                      |
| --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Subsidiary plans (scope, requirements, schedule, cost, quality, resource, comms, risk, procurement, stakeholder engagement) | Project schedule, cost and duration estimates, basis of estimates |
| Scope, schedule and cost baselines                                                                                          | Risk register, issue log, assumption log, change log              |
| Change and configuration management plans, PMB, life cycle, development approach                                            | Lessons learned register, requirements documentation              |

- **Performance measurement baseline (PMB)** = scope + schedule + cost baselines. Quality, risk and resources are not part of it.
- **Estimating:**
  - Analogous: early, a similar precedent, fast, less accurate.
  - Parametric: unit rate × quantity from a validated model.
  - Bottom-up: from decomposed work packages; most accurate, most effort.
  - Three-point: beta/PERT = (O + 4M + P) ÷ 6; triangular = (O + M + P) ÷ 3. O = 6, M = 9, P = 18 gives 10 (beta) and 11 (triangular).
  - Planning poker (team sizes items together) and affinity estimating (many items into size buckets).
- **Effort is not duration.** 120 hours shared by three people at a quarter of an 8-hour day each = 6 hours/day = 20 working days.
- **Capacity-adjusted velocity:** apply every reduction. 40 points × 0.8 (one of five people out) × 0.8 (two of ten days training) ≈ 26 points.
- **Re-estimate** when the people assigned differ from the people who estimated.
- **Consolidated plan review:** a known conflict (training before installation, one specialist booked twice) is an issue to resolve now with the plan owners, not a risk to log.
- **Dependencies:** mandatory (hard logic), discretionary (preferred/soft; the only kind fast tracking can relax), external, internal.
- **Continued value:** compare remaining cost with remaining benefit; sunk cost is excluded. $1.5M left to spend for a $2.5M benefit still returns $1M. The PM analyzes and surfaces it; the sponsor decides.
- **Maintaining the plan:** rolling wave detail inside a planning package's budget and dates is maintenance. Moving an external commitment, the approved budget or a baselined milestone needs change control.
- **Data for decisions:** EMV (probability × impact added to base), what-if scenarios, variance analysis (now vs plan), trend analysis (direction and end point). $480k + 40% × $120k = $528k beats $500k + 20% × $150k = $530k.

**Traps**

- The schedule baseline is a plan component; the project schedule is a document. The change management plan is a component; the change log is a document.
- A worsening trend inside its threshold still needs analysis and a forecast.

📖 Full lesson: [PMP Integrated Project Management Plan: Approach, Estimating and Plan Delivery](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-integrated-project-management-plan/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.2 Develop and manage project scope

- **Three enablers:** define scope, obtain stakeholder agreement, break down scope. "Manage" means agreed scope changes only by the agreed route.

| Elicitation technique | Fits best when                                                        |
| --------------------- | --------------------------------------------------------------------- |
| Interviews            | Detailed or sensitive information from a few people                   |
| Facilitated workshop  | Several groups disagree and cross-functional agreement is needed fast |
| Focus group           | Gauging a group's expectations and attitudes                          |
| Questionnaire/survey  | Large, dispersed audience                                             |
| Observation           | Users cannot describe their routine (tacit, habitual)                 |
| Prototyping           | Users cannot specify what they want but react when they see it        |
| Benchmarking          | Setting targets from others' practices                                |
| Document analysis     | Requirements already exist in writing                                 |

- **Project scope statement:** product scope description, deliverables, acceptance criteria, exclusions. Charter authorizes; scope management plan describes the method; requirements documentation captures needs; scope statement sets the boundary.
- **Exclusion vs assumption:** confirmed out of scope → exclusion in the scope statement. Uncertain but treated as true → assumption log.
- **Acceptance criteria** are per item and objectively checkable ("confirmation email within one minute", not "user-friendly"). Quality metrics live in the quality plan and measure work generally.
- **Definition of ready** is the entry condition for an iteration; **definition of done** is the exit standard for all work; several teams on one product share one definition of done (Scrum Guide).
- **Agreement:** facilitate against the business objectives first; escalate to the sponsor only what facilitation cannot resolve. Agile agreement is a release goal plus a prioritized feature set.
- **Requirements traceability matrix:** requirement → source → deliverable/story → test. In regulated agile work, keep it current story by story.
- **WBS rules:**
  - Deliverable-oriented (nouns). Verb phrases are activities and belong in the schedule.
  - **100% rule:** all in-scope work, nothing excluded, children sum to the parent, including a project management branch.
  - Stops at **work packages** (estimable, assignable, monitorable). 8/80 is a heuristic.
  - Reserves are not scope: contingency (in the cost baseline, known-unknowns); management reserve (outside it, unknown-unknowns).
- **Control account** (integrates scope, budget, schedule for EVM) → **planning package** (known but not detailed, carries budget) → **work package** → activities (schedule).
- **WBS dictionary:** per-component detail (description, responsible organization, milestones, cost, quality requirements, acceptance criteria). Settles boundaries between packages.
- **Scope baseline** = approved scope statement + WBS + WBS dictionary. Changes go through change control whoever raises them. Structural change → update WBS and dictionary; detail change only → update the dictionary entry.
- **Agile breakdown:** epic → feature → user story (fits one iteration) → task; a spike is a time-boxed investigation. INVEST stories, split as **vertical slices**. Backlog refinement is agile rolling wave.
- **Acceptance order:** control quality (team verifies) then validate scope (customer accepts). In agile, the product owner accepts against criteria and the definition of done; a story missing one criterion goes back to the backlog.
- **Scope creep** (requested, unapproved) vs **gold plating** (team-initiated, unrequested). Agile: redirect requests to the product owner. Hybrid: route by the component the change touches.
- **Hybrid scope:** baseline fixed or mandated components; manage emerging ones in a backlog; show the agile stream in the WBS at feature or release level.

**Traps**

- A sponsor from the performing side cannot accept on the customer's behalf.
- Uncertain later work is not left out of the WBS; it sits as a planning package.

📖 Full lesson: [PMP Scope Management: Requirements, Scope Statement, WBS and Backlog](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-develop-manage-project-scope/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.3 Help ensure value-based delivery

- **Six enablers:** identify value components, prioritize by value and feedback, deliver incrementally, examine business value throughout, verify a benefits measurement system, and evaluate delivery options to demonstrate value.
- **Define value with the stakeholders who hold it,** as measurable outcomes, before prioritizing. Facilitate rather than author; reconcile conflicting definitions with them and the sponsor. Count value net of the costs it creates for other groups.
- **Tangible** value is measured directly (revenue, cost, cycle time). **Intangible** value (reputation, morale, trust) stays in the business case with an agreed indirect proxy, baseline and target.
- **MoSCoW:** must, should, could, won't (this time). Drop could-haves first, then should-haves, never must-haves. DSDM recommends must-haves at no more than about 60% of effort; too many must-haves removes the contingency.
- **Kano:** basic (missed when absent), performance (more is better), excitement (delights), indifferent (candidate to drop). Basic and indifferent look alike when present; the absence test separates them. Delighters drift into basics.
- **WSJF** = cost of delay ÷ duration. P 12/3 = 4.0, Q 30/10 = 3.0, R 6/1 = 6.0 → order R, P, Q. Time-critical value (a filing season, a regulatory date) has a higher cost of delay.
- **Reprioritizing from feedback:** agile → product owner reorders the backlog, acted on at the next planning (a valid iteration goal is left to finish); predictive → change control; hybrid → each component keeps its own route.

| Term                             | Purpose                                                                 |
| -------------------------------- | ----------------------------------------------------------------------- |
| Minimum marketable feature (MMF) | Smallest standalone piece with customer value; starts the return        |
| Minimum viable product (MVP)     | Smallest version built to test a hypothesis                             |
| Walking skeleton                 | Thin end-to-end build that proves the architecture                      |
| Potentially shippable increment  | Done output of an iteration; releasable, not necessarily valuable alone |

- **Incremental release:** a constraint (approval, certification) holds back only the parts it governs. A fixed per-release cost makes batch size an economic choice. Predictive projects deliver incrementally through phased handovers or staggered go-lives; crashing and fast tracking only bring the single end date forward.
- **Business case is living:** review it at phase gates and when assumptions change; bring the revised picture to the sponsor. Green CPI and SPI say nothing about benefits.

| Measure            | Tells you                      | Rule                          |
| ------------------ | ------------------------------ | ----------------------------- |
| NPV                | Value created in today's money | Higher is better              |
| Payback period     | Time to recover the investment | Shorter; often a cash screen  |
| Benefit-cost ratio | Benefits per unit of cost      | Above 1 is worthwhile         |
| IRR                | Discount rate at which NPV = 0 | Higher than the required rate |

- **NPV decides** between mutually exclusive options. Payback is a filter only when the organization states one: screen first, then rank survivors by NPV.
- **Benefits management plan:** metric, baseline, target, timing, owner, assumptions, risks. Capture the baseline **before** go-live; the owner is an operational manager who outlasts the project; hand over the data source. The project closes before benefits are realized.
- **Outputs** (velocity, features, CPI/SPI) show delivery. **Outcomes** (lagging) show value. **Leading indicators** move soon after release and predict the outcome. If outputs are strong and outcomes flat, diagnose with stakeholders.
- **Demonstrate value with evidence that matches the doubt:** pilot (real outcome, small scale), simulation on historical data, A/B test (two working versions at the same time), prototype usability test (when real use is not allowed yet), demo (shows features, not outcomes).

**Traps**

- MMF is about earning value; MVP is about learning.
- A leading indicator that stops predicting the outcome is revisited with the benefits owner.

📖 Full lesson: [PMP Value-Based Delivery: Prioritization, Incremental Value and Benefits](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-value-based-delivery/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.4 Plan and manage resources

- **Two enablers:** define and plan resources from requirements; manage and optimize resource needs and availability. Resources are **team** (employees, borrowed staff, contractors) and **physical** (equipment, materials, facilities, environments).
- **Resource management plan:** how resources are identified, acquired, developed, managed, recognized, controlled and released. Not the procurement plan (buying from sellers), cost baseline, or risk register.
- **Derive needs from requirements:** type and skill, quantity, timing, and lead time. Start acquisition at least one lead time ahead. An approved change is not complete until the resource plan reflects it.

| Structure | Breaks down                         | Question                                              |
| --------- | ----------------------------------- | ----------------------------------------------------- |
| WBS       | Deliverables and work               | What work must be done?                               |
| RBS       | Resources by category and type      | What kinds of resource, and how much?                 |
| OBS       | The performing organization's units | Which unit owns which work?                           |
| RAM/RACI  | Work against people or roles        | Who is responsible, accountable, consulted, informed? |

- **Resource calendar** shows when a specific resource can work (part-time, leave, regional holidays). The project calendar cannot. A missing holiday → update calendars and reanalyze before choosing a fix.
- **Acquisition methods:** pre-assignment (named in a proposal or contract), negotiation (functional managers in a matrix), multicriteria decision analysis (transparent weighted selection), virtual teams, acquisition from outside (procurement). A named key person is replaced only through the contract's substitution terms.
- **Resource histogram** compares planned load with availability per period; bars over the line are overallocation. Confirm with data before reacting.

|                             | Resource smoothing               | Resource leveling                          |
| --------------------------- | -------------------------------- | ------------------------------------------ |
| Moves activities            | Only within free and total float | Whenever needed to respect limits          |
| Finish date                 | Unchanged                        | May extend                                 |
| Critical path               | Unchanged                        | May change; a new path can become critical |
| Removes all overallocation? | Not always (capped by float)     | Yes, at the cost of time                   |

- **Fixed finish date:** smooth what has float; add qualified capacity on critical work if funded; otherwise trade scope, quality or date through change control. A leveled date past the baseline is a change request, not a silent rebaseline.
- **Date can move but no extra people or overtime, no float:** leveling fits.
- **Crashing and fast tracking** shorten schedules; neither resolves overallocation, and fast tracking usually adds load.
- **Shared resources:** negotiate with the functional manager first; escalate to the sponsor with impact and options when negotiation is exhausted. Cross-project strategic choices go to program or portfolio governance. For a shared test environment: one visible booking calendar plus a governance-agreed priority rule.
- **Agile:** dedicated, stable teams give predictable velocity. Capacity = velocity × availability (30 points × 4/5 = 24). Adding people slows a team at first. Spread bottleneck skills by pairing and swarming (T-shaped people). Close skills gaps before the work depends on them.
- **Physical resources:** just-in-time delivery, book shared equipment at planning, group rental days and confirm ahead of the lead time.
- **Control:** explain a variance before correcting it. When someone resigns, assess impact and arrange a handover while they are still there.
- **Release early** when the need ends, agreed with the lending manager and with a handover; formal team release at the end belongs to closure.

**Traps**

- A schedule with no late activities can still hide an overloaded crew.
- Overtime adds hours to someone who is already overloaded.

📖 Full lesson: [PMP Resource Management: Planning, Acquiring and Optimizing Project Resources](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-plan-manage-project-resources/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.5 Plan and manage procurement

- **Ten enablers** spanning planning, contract type, vendor performance, verifying objectives, negotiation, supplier management, procurement strategy and a delivery solution. Two ideas run through all of them: **the contract governs**, and the **PM participates but procurement holds contract authority**.
- **Make-or-buy** comes before any bid document. Count direct cost, opportunity cost (internal people pulled off revenue work) and non-cost factors (skills, IP, confidentiality, control).
- **Lease or buy break-even** = purchase cost ÷ (daily lease − daily running cost if bought). $9,000 ÷ ($450 − $150) = 30 days. Need it longer → buy.
- **Bid documents:** RFI (learn the market), RFQ (fully specified item, compare price), RFP (sellers propose an approach). Widely varying bids point to an imprecise **statement of work**; tighten it.
- **Procurement management plan:** contract types, authority, weighted selection criteria, independent estimates, documents and timetable.

| Contract | Fits when                                          | Cost risk                                |
| -------- | -------------------------------------------------- | ---------------------------------------- |
| FFP      | Scope fully specified and stable                   | Seller                                   |
| FPIF     | Defined scope, reward targets                      | Mostly seller, shared to a ceiling price |
| FP-EPA   | Long contract, volatile input price                | Seller, except the indexed price         |
| T&M      | Buying capacity or small undefined work            | Buyer; cap with not-to-exceed            |
| CPFF     | Uncertain scope; fee fixed on the initial estimate | Buyer                                    |
| CPIF     | Uncertain scope, motivate cost control             | Buyer, savings/overruns shared           |
| CPAF     | Reward subjectively judged performance             | Buyer; award at buyer's discretion       |

- **Incentive math** (ratio is buyer/seller): variance = actual − target cost; seller's share adjusts the fee; total = actual cost + fee. FPIF is capped at the ceiling price; cost-plus has no ceiling.
  - FPIF: target $50k, fee $5k, 70/30, ceiling $60k, actual $56k → overrun $6k, seller bears $1.8k, fee $3.2k, price $59.2k.
  - CPIF: target $80k, fee $8k, 80/20, actual $70k → underrun $10k, seller gains $2k, fee $10k, buyer pays $80k.
- **Source selection:** score against the agreed weighted criteria. Investigate bids far from the independent cost estimate (misread SOW). Share every clarification with all bidders. Disclose a conflict of interest and step aside.
- **Negotiation:** rank must-haves vs tradeables, set a walk-away point, know your **BATNA**, confirm who on each side can agree terms. Collaborative stance with strategic vendors.
- **Managing suppliers:** evaluate with the contract's measures (reviews, inspections, audits, SLAs). Apply contractual remedies in proportion; termination is for serious or persistent breach. Payment follows the acceptance record when terms say so. A need the contract does not cover → performance discussion, then amendment. **Privity:** subcontractor requests go through the seller.
- **Contract change control:** every change to the seller's work becomes an amendment, even under FFP. Informal direction creates a **constructive change**, handled as a claim.
- **Claims:** decide entitlement first, then amount. Negotiate → ADR (mediation, arbitration) per the contract → litigation last. Settle before closure where possible.
- **Closing a procurement:** deliverables accepted, claims settled, final payment, formal written notice, procurement audit, seller performance record, archive.
- **Strategy:** match contract type to how defined each package is. Phase discovery (T&M) then build (fixed price). Design-bid-build keeps design control with the buyer; design-build gives one accountable party and overlap.
- **Agile contracting:** master agreement plus schedules, not-to-exceed T&M, fixed-price increments, early cancellation, dynamic scope (swap equal-sized items), team augmentation.
- **Delivery solution:** in-house (strategic, capability exists), COTS (common need, accept product's way of working), outsource (rare need), mixed team with skills transfer (long-term ownership needed).

**Traps**

- The PM analyzes proposals at the table; only the authorized signatory commits the buyer.
- Private answers to one bidder can invalidate the process.

📖 Full lesson: [PMP Procurement Management: Contract Types, Negotiation and Vendor Management](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-procurement-management-contract-types/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.6 Plan and manage finance

- **Seven enablers:** analyze financial needs, quantify contingency, plan spend tracking, plan reporting, anticipate challenges, monitor variations with governance, manage reserves.
- **Estimating:** analogous scales a past project's **total**; parametric multiplies a **unit rate** by a quantity; bottom-up rolls up work packages (most accurate); three-point gives a range. Build expected **escalation** (inflation) into each period's estimates. Compare options on **life-cycle cost** when total cost to the organization matters.

| Layer                   | Contains                                      | Controlled by                   |
| ----------------------- | --------------------------------------------- | ------------------------------- |
| Work package estimates  | Planned work, rolled up                       | PM and control account managers |
| Contingency reserve     | Identified risks (known-unknowns)             | PM, inside the baseline         |
| **Cost baseline = BAC** | Estimates + contingency                       | Change control                  |
| Management reserve      | Unidentified in-scope work (unknown-unknowns) | Management/sponsor              |
| **Project budget**      | Cost baseline + management reserve            | Sponsor and governance          |

- **Contingency by EMV:** sum probability × impact; opportunities offset threats. 15% × $60k + 10% × $80k − 20% × $15k = $14k. Fund a planned response as work, then size contingency on the **residual** risk.
- **Monte Carlo:** contingency = cost at the chosen confidence (e.g. P80 $2.3M) − base estimate ($2.0M) = $300k. The sponsor's appetite picks the level.
- **Reserves in use:**
  - Identified risk occurs → draw its contingency; BAC unchanged.
  - Unidentified work → change request to release management reserve; BAC rises.
  - Risk closes → release its allocation per policy.
  - Exposure outgrows contingency → request more via change request, early.
  - BAC $800k: spend $15k contingency → still $800k; approved $25k management reserve → $825k.
- **Cost management plan:** units, precision, accuracy range, control thresholds, EV crediting rules, reporting formats. Use 0/100 or 50/50 for short packages and weighted milestones for long ones to stop optimistic percent-complete inflating EV.
- **Actual cost** is recorded when work is performed (include **accruals**). Signed purchase orders are **commitments**, tracked against funding, not AC. The **S-curve** plots cumulative PV, EV and AC.
- **Agile finance:** remaining cost = burn rate × iterations remaining ($50k × 6 = $300k). Fixed budget → scope flexes. Incremental funding releases tranches after reviews. Hybrid: EVM for predictive components, burn rate and cost per feature for agile ones.

| Measure | Formula                    | Measure       | Formula                 |
| ------- | -------------------------- | ------------- | ----------------------- |
| CV      | EV − AC                    | CPI           | EV ÷ AC                 |
| SV      | EV − PV                    | SPI           | EV ÷ PV                 |
| ETC     | EAC − AC (or new estimate) | VAC           | BAC − EAC               |
| TCPI    | (BAC − EV) ÷ (BAC − AC)    | TCPI (to EAC) | (BAC − EV) ÷ (EAC − AC) |

| Situation                     | EAC                           |
| ----------------------------- | ----------------------------- |
| Cause will continue (typical) | BAC ÷ CPI                     |
| One-off (atypical)            | AC + (BAC − EV)               |
| Original estimates flawed     | AC + new bottom-up ETC        |
| Cost and schedule both matter | AC + (BAC − EV) ÷ (CPI × SPI) |

- BAC $600k, EV $240k, AC $300k: CPI 0.8 → typical EAC $750k; atypical EAC $660k.
- **TCPI far above CPI** (BAC $2.0M, EV $0.9M, AC $1.1M: TCPI ≈ 1.22 vs CPI ≈ 0.82) means the budget is unrealistic: report honestly and take it to governance. Management reserve is not for poor performance.
- **Reporting:** executives want EAC, VAC and a time-phased forecast. VAC is the one figure for "how far over or under at the end". Agile funders want spend per iteration beside value delivered.
- **Variances:** analyze cause first; act within authority or escalate as the plan defines; escalate a forecast breach when seen. Rebaseline only for approved changes, never to hide overruns.
- **Underspend is not automatically a saving:** PV $500k, EV $350k, AC $340k → CPI ≈ 1.03, SPI 0.70; the money is still needed for late work.
- **Funding limits:** when a period's planned spend exceeds its limit, move work with float into the next period (via change control once baselined). Reserves and fast tracking do not fix timing. Raise forecast tranche breaches early.
- **Anticipate:** exchange-rate exposure (work with treasury), escalation and price indices with trigger points, possible funding cuts (pre-plan the reduced scope), and EAC/VAC/TCPI trends.

**Traps**

- Contingency is already in the baseline; adding it again to the budget double-counts.
- Story points are a planning measure, not a currency.

📖 Full lesson: [PMP Cost and Finance Management: Budget, Reserves and Earned Value](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-project-cost-budget-financial-management/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.7 Plan and optimize quality of products/deliverables

- **Seven enablers:** gather quality requirements, plan quality processes and tools, execute the quality plan, ensure regulatory compliance, manage cost of quality and sustainability, run ongoing reviews, improve continuously.
- **Quality vs grade:** quality is meeting requirements; grade is the feature level. Low grade can be fine; low quality never is. Cut cost by lowering grade (where every requirement is still met), not by dropping quality activities.
- **Precision** = repeated measurements close together; **accuracy** = close to the target value.
- **Gather quality requirements during planning** from every user group, regulations, standards, organizational process assets and sustainability commitments. Functional acceptance criteria rarely say how well or under what conditions. An overlooked user group is a requirements gap: elicit their needs and bring them in via the backlog or change control.
- **Quality metric** = measurable attribute + target + tolerance, tied to what the customer values, checked at an agreed point. Anything inside the tolerance conforms (500 ml ± 5 ml: 497 ml is fine; reworking it is waste).
- **Quality management plan:** standards, objectives, roles, what is reviewed, planned audits/inspections/tests, tools, nonconformance handling. Dropping or swapping a planned check under schedule pressure is a plan change through change control. A hybrid project has one plan with different activities per approach.

|            | Manage quality                                                            | Control quality                                   |
| ---------- | ------------------------------------------------------------------------- | ------------------------------------------------- |
| Focus      | The process                                                               | The output                                        |
| Question   | Will our way of working produce compliant results?                        | Does this deliverable meet its requirements?      |
| Activities | Quality audits, process analysis, design for quality, root cause analysis | Inspection, testing, check sheets, control charts |

- **Recurring defects call for process work:** audit whether the process is followed; if it is and defects persist, process analysis finds the step to redesign. More end inspection changes nothing.

| Tool                | Use it to                                                  |
| ------------------- | ---------------------------------------------------------- |
| Check sheet         | Tally defects by type as they occur                        |
| Pareto chart        | Rank categories by frequency to find the vital few (80/20) |
| Histogram           | Show the distribution of one variable                      |
| Scatter diagram     | Test whether two variables are related                     |
| Fishbone (Ishikawa) | Explore many possible causes of one problem in categories  |
| Five whys           | Drill one failure down to a changeable process cause       |
| Control chart       | Judge whether a process is stable over time                |

- **Control chart:** control limits (typically ±3 standard deviations) describe the process; specification limits describe the requirement.
  - Point outside a control limit → investigate for an assignable cause, even if the unit is in spec.
  - **Rule of seven:** seven consecutive points on one side of the mean → investigate.
  - Stable but limits wider than spec → not capable; improve the process.
  - Stable and capable → leave it alone. Adjusting a stable process for common-cause noise is **tampering**.
- **Regulatory compliance:** bring in compliance or legal experts to identify the rules first; put recurring checks in the definition of done; record evidence as the work happens. Compliance requirements are not the project's to reinterpret.

| Cost of quality  | Type           | Examples                                                   |
| ---------------- | -------------- | ---------------------------------------------------------- |
| Prevention       | Conformance    | Training, design reviews, standards, work instructions     |
| Appraisal        | Conformance    | Inspections, testing, output audits, test equipment upkeep |
| Internal failure | Nonconformance | Rework, scrap, retesting, defect delays                    |
| External failure | Nonconformance | Warranty, field fixes, recalls, lost business              |

- Shift effort toward prevention and early detection, but only to the **economic level of conformance**. Consider the deliverable's whole life, not only the project budget.
- **Sustainability criteria** are measurable quality requirements: they change only through change control, and missing one is a nonconformance whose disposition (correct, waiver, later fix) is agreed with the customer.
- **Quality audit:** independent review of whether activities follow policies and procedures; identifies good practices and gaps, shares them, contributes to lessons learned. Act on a lapsed control even before defects appear.
- **Built-in quality (agile):** continuous integration with automated regression tests, peer review or pairing, test-first practices, and a definition of done held under pressure. A need that applies to every item belongs in the definition of done, not each story's acceptance criteria.
- **Continuous improvement:** PDCA (Shewhart, popularized by Deming), retrospectives, Kaizen. Try a few changes at a time, measure against a baseline, pilot before wide adoption, and apply lessons to remaining work. Root cause analysis before fixes.

**Traps**

- Pareto ranks categories; fishbone explores the causes of one problem.
- Happy stakeholders at a review do not prove quality if escaped defects are rising.

📖 Full lesson: [PMP Quality Management: Cost of Quality, Quality Tools and Continuous Improvement](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-quality-management-cost-of-quality/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.8 Plan and manage schedule

- **Eight enablers:** prepare a schedule for the approach, coordinate with other projects and operations, estimate tasks, use benchmarks and history, create, baseline, execute the schedule management plan, analyze variation.

| Approach              | Schedule form                                                 |
| --------------------- | ------------------------------------------------------------- |
| Predictive            | Network with logic, durations, critical path and float        |
| Adaptive (iterations) | Roadmap, release plan, fixed-length iterations                |
| Adaptive (flow)       | Kanban with WIP limits, continuous pull, throughput forecasts |
| Hybrid                | Milestones anchoring predictive networks and adaptive cadence |

- **Detail follows certainty.** Contract milestones still bind adaptive streams.
- **Timeboxes are fixed:** unfinished items return to the backlog for the product owner to re-order. When unplanned work dominates and arrives without warning, switch to flow rather than changing the iteration length.
- **Relationships:** FS (default), SS (run alongside), FF (completion depends on the other's completion), SF (rare; old runs until new starts). Pick by which end is actually constrained.
- **Lead** = overlap (real parallel work). **Lag** = a wait with no work, resources or cost (curing, drying). A wait that needs effort is an activity.
- Two relationships on one pair: the later constraint wins (excavation 10 days; lining 5 days with SS+3 and FF+4 → lining finishes end of day 14).
- **Dependencies:** mandatory (hard), discretionary (soft; can be overlapped), external, internal.
- **Milestones** have zero duration and are achieved or not; never "90% complete". Milestone charts suit governance. When a hybrid milestone slips, first re-order the backlog with the product owner.
- **Story points** are relative and team-specific; never compare velocity across teams or use it as a target (estimate inflation).
- **Evidence weighting:** the organization's own actuals on comparable work > the doers' estimates and lessons learned > industry benchmarks (a sanity check). A sponsor's target date is a constraint, not an estimate.

|           | Total float             | Free float                                              |
| --------- | ----------------------- | ------------------------------------------------------- |
| Protects  | The project finish date | The next activity's early start                         |
| Calculate | LS − ES (or LF − EF)    | Earliest successor ES − this activity's EF (FS, no lag) |
| Size      | ≥ free float            | ≤ total float                                           |

- Total float 6, free float 1, slip 3 → successor starts 2 days late; finish unchanged.
- **Critical path** = longest path (shortest possible duration). P(2)→Q(8)→T(2) = 12 vs P→R(4)→S(3)→T = 11: critical path P-Q-T; R and S have 1 day of float.
- **Near-critical paths:** crashing path 1 (40 days) by 6 when path 2 is 37 gains only 3 days. Recheck after each step. Monte Carlo gives finish dates with confidence levels.

|             | Crashing                                   | Fast tracking                                       |
| ----------- | ------------------------------------------ | --------------------------------------------------- |
| Changes     | Adds resources, overtime, premium delivery | Overlaps sequential activities                      |
| Costs       | Money                                      | Risk of rework, coordination                        |
| Works on    | Critical, resource-driven activities       | Critical activities with discretionary dependencies |
| Choose when | Money available, low risk tolerance        | No extra spend, more risk acceptable                |

- **Least-cost crashing:** critical activities only, cheapest per day first, within crash limits. Gain 3 days on K-L-M: K 1 day ($700) + M 2 days ($1,900) = $2,600; non-critical N buys nothing.
- **Coordinate** with operations calendars (peaks, change freezes) and agree windows with their owners; record external dependencies with owners and buffer. Agile teams sharing a release: bring product owners together. Escalate cross-project priority conflicts on the critical path to the program manager or portfolio governance.
- **Schedule baseline** changes only for approved changes; performance slips stay as variance with corrective action. Baseline adaptive streams at release milestones and cadence, not story level.
- **Schedule management plan:** method and tool, units, update cadence, control thresholds, performance measurement rules (0/100, 50/50, 20/80), reporting formats, iteration length. Keep the update cadence even when a team says it is on track.
- **SV = EV − PV; SPI = EV ÷ PV** (PV $250k, EV $225k → SV −$25k, SPI 0.90). SPI can look healthy while the critical path slips, and drifts back to 1.0 after the planned finish; use forecast finish dates or earned schedule SPI(t).
- **Adaptive tracking:** release burnup separates delivery from scope change; burndown can hide scope growth; throughput forecasts "when"; cycle time answers "how long for one item". Forecast as a range.
- **Fixed date:** iterations × low and high velocity. 5 × 18–26 → commit 90 points, show up to 130 as possible.

**Traps**

- The critical path is the longest total path, not the path with the single longest activity.
- Crashing a fixed-duration activity (curing) or fast tracking a mandatory dependency does not work.

📖 Full lesson: [PMP Schedule Management: Critical Path, Float, Baselines and Agile Forecasting](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-schedule-management-critical-path/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.9 Evaluate project status

- **Eight enablers:** develop metrics, analysis and reconciliation; identify and tailor artifacts; keep artifacts created, reviewed, updated and documented; keep them accessible; assess progress; measure, analyze and update metrics; communicate status; assess artifact management.
- **Output** metrics count what was produced; **outcome** metrics show the effect on the business. **Lagging** indicators confirm what happened; **leading** indicators (open design queries, approval backlog, rising WIP) give early warning.
- **Metrics that mislead:** vanity metrics, Goodhart's law (a measure that becomes a target gets gamed), velocity compared across teams, and single metrics that hide trade-offs (pair speed with quality).

| Crediting method          | Fits                                                 |
| ------------------------- | ---------------------------------------------------- |
| 0/100                     | Very short packages (within one reporting period)    |
| 50/50 or 20/80            | Short packages of one or two periods                 |
| Weighted milestones       | Long packages with verifiable stages                 |
| Percent complete          | Only with an objective basis; least reliable         |
| Physical measurement      | Countable, repetitive work                           |
| Level of effort (EV = PV) | Genuine support work only; never shows SV            |
| Apportioned effort        | Work tied to another package (inspection of a build) |

- **Agile:** a story earns credit only when it meets the definition of done and is accepted (effectively 0/100). Velocity counts accepted work only.
- **SV = EV − PV, SPI = EV ÷ PV, CV = EV − AC, CPI = EV ÷ AC.** PV 800, EV 880, AC 1,000 → SPI 1.10, CPI 0.88: ahead but over budget.
- **Where indices mislead:** SPI is blind to the critical path; SPI returns to 1.0 at completion; a good CPI with poor SPI usually means work not yet performed; watch period-by-period trends.
- **Burndown** nets scope added against work done; **burnup** shows completed work and total scope separately. Parallel burnup lines mean no finish can be forecast until scope is addressed. Late steep burndown = work finishing in large late batches.
- **Release forecast as a range:** 150 points at 25–30 per iteration = 5–6 iterations, stated with its basis. Investigate velocity changes with the team; never set velocity targets.

| Flow metric | Measures                       |
| ----------- | ------------------------------ |
| Lead time   | Request made → delivered       |
| Cycle time  | Work started → delivered       |
| Throughput  | Items finished per period      |
| WIP         | Items started but not finished |

- **Cumulative flow diagram:** a steadily widening band is a bottleneck; limit WIP there. **Little's Law:** cycle time = WIP ÷ throughput. Forecast from cycle-time history ("85% within 9 days").
- **Inside the threshold is not automatically fine:** analyze a worsening trend before it breaches. Root cause before corrective action.
- **Reconcile conflicting sources** (timesheets vs verified units, supplier claim vs inspections) before reporting; rely on the most objective evidence and agree completion criteria.
- **Hybrid roll-up:** agile percent complete = accepted work ÷ current release scope. Map each stream's forecast onto shared milestones; a joint milestone is only as early as its latest critical dependency.
- **Status content:** progress against baseline, forecast with basis, trends, causes and responses, material risks and issues, decisions needed. Report slips now, with the recovery plan; no "watermelon" reports.
- **Artifacts:** tailor the set with the PMO; apply full rigour only where regulated. One owner per artifact (the product backlog belongs to the product owner), one controlled version, approved changes flow to every affected artifact.

| Log            | Records                                             |
| -------------- | --------------------------------------------------- |
| Issue log      | Current problems with owner, date, status           |
| Risk register  | Uncertain events with probability, impact, response |
| Assumption log | Assumptions and constraints the plans rely on       |
| Change log     | Change requests and decisions                       |
| Decision log   | Decisions, who made them, and why                   |

- **Accessibility:** one shared repository, role-based access, screen-reader-friendly formats. Effective artifact management = used, current, trusted. Retire an unused artifact only after confirming no stakeholder, contract or audit depends on it.

**Traps**

- Comparing AC with PV says nothing about efficiency.
- Cadence is not convergence: holding every iteration on time does not prove the release scope will finish by the milestone.

📖 Full lesson: [PMP Project Status: Metrics, Earned Value, Burn Charts and Status Reporting](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-evaluate-project-status-metrics-reporting/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

## 2.10 Manage project closure

- **Four enablers:** obtain stakeholder approval of completion, determine closure criteria, validate readiness for transition, conclude closing activities (lessons learned, retrospectives, procurement, financials, resources). They apply to phases, whole projects and cancelled projects alike.
- **Closure criteria** are measurable, agreed during planning by the sponsor, customer and receiving owner, and achievable before the project ends. Long-term benefits belong in the benefits management plan and are tracked after closure.
- **Disputed completion:** review the agreed criteria and evidence with the stakeholder. New expectations raised at closure are changes or follow-on work.

| Approach   | Closure trigger                                               | Decided by                                                        |
| ---------- | ------------------------------------------------------------- | ----------------------------------------------------------------- |
| Predictive | Scope baseline delivered, accepted, criteria met              | Sponsor or customer named in plan/contract                        |
| Agile      | Product goal met, or remaining value no longer justifies cost | Sponsor/funding body in the charter, advised by the product owner |
| Hybrid     | Each component meets its own criteria, plus shared ones       | Authority in the governance plan                                  |

- An agile project does **not** end when the backlog is empty. Remaining important items move to the ongoing owner's backlog with their agreement.
- **Deliverable acceptance** (one output, throughout delivery) ≠ **completion approval** (whole project or phase, from the authority the governance plan or contract names). Record approval in writing.
- **Phase gate:** go, go with conditions, hold/repeat, or stop. The next phase does not start before the decision. Unmet exit criteria are analyzed and presented, never waived unilaterally.
- **Transition readiness** is proven by the receiving team doing the work: completed training, supervised dry runs, runbooks the operations owner accepted, an agreed checklist. The project team's own test is weaker evidence.
- **Readiness gaps:** analyze with the receiving owner first, then take timing decisions to the sponsor. **Hypercare** is time-boxed, with exit criteria and the owner's agreement. Punch-list items get owners and dates.
- **Final lessons learned:** consolidate the register kept all project, review with team and stakeholders, write neutrally (event, cause, effect, not blame), archive in the organizational repository. The **final retrospective** covers the whole project for future teams; findings outside the team's control go to the process owner.
- **Procurement closure:** confirm obligations complete, settle contractual payments (including retained amounts), resolve every claim, send formal notice, archive the contract file. A contract with an open claim is not closed. A cancelled contract is closed under its termination terms.
- **Financial closure:** reconcile committed but unbilled costs, close cost accounts, return unused contingency and budget (not a fund for new scope), report final cost against budget.
- **Release resources** as their work ends, honour transition commitments, give functional managers performance input, return equipment, licences and access.
- **Final report:** objectives and criteria met, performance against scope, schedule, cost and quality, value delivered and who tracks remaining benefits, transition status, risks, issues, lessons.
- **Archive** under the retention policy and any contractual or data-protection obligations.
- **Terminated project:** record why and the state of the work, hand usable outputs to an owner, terminate contracts under their terms, close finances, capture lessons, get the sponsor's acknowledgement.

**Traps**

- Statements of satisfaction from senior people are evidence, not approval.
- Leftover reserve is returned, not spent on an end-of-project feature request.

📖 Full lesson: [PMP Project Closure: Completion Criteria, Transition, Lessons Learned and Closing Contracts](https://www.savemycert.com/revision/pmp-project-management-professional/pmp-project-closure-lessons-learned-transition/?utm_source=github&utm_medium=readme&utm_campaign=pmp-study-guide)

[← Back to the study guide](../README.md)
