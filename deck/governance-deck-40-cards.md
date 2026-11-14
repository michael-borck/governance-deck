# The Governance Deck — 40 cards

Forty cards for executives and boards approving and overseeing AI, distilled
from the generic frameworks of Leading AI with Confidence. Five sections:
**The Line** (8), **Oversight** (10), **Data** (8), **Vendors** (8),
**Learning** (6).

One card type: why it goes wrong, the move, the line. The test for every card:
does it produce a named owner, a piece of evidence and a review date? If not,
it is decoration.

**The tools change. Accountability does not.**

---

## THE LINE · Accountability and the gate

### 01 · The accountability principle
**Why it goes wrong:** Accountability gets treated as a vibe ("the AI did it") or a committee. Neither can sign.

**The move:** For every AI-assisted decision: one named human who owns the evidence and the consequence. Auditability is part of the decision, not the audit team's afterthought.

*"AI can accelerate situational awareness. It can never hold accountability."*

### 02 · The four questions
**Why it goes wrong:** Tool approvals drift into feature comparisons, and the due diligence never happens.

**The move:** Of every tool: what does it actually do? What does it see? Who checks it? What happens when it is wrong?

*"If a tool can't answer the four, it isn't approved — it's tolerated."*

### 03 · What cannot be automated
**Why it goes wrong:** Capability demos make every decision look automatable.

**The move:** Name the decisions that are unbounded — the context arrives in real time, the right call may go against the data, the variables cannot all be listed — and who owns each one.

*"The list of what AI may not decide is the first governance document."*

### 04 · Owner, evidence, review date
**Why it goes wrong:** Frameworks get admired during the offsite and forgotten after it.

**The move:** Run every governance artefact through the test: does it produce a named owner, a piece of evidence and a review date? If not, cut it.

*"No owner, no evidence, no review date — it is decoration."*

### 05 · The use-case gate
**Why it goes wrong:** Use cases start as pilots and become infrastructure without passing any gate.

**The move:** The one-page approval: use case and owner · does / does not do · data class and approved tool · tier and its evidence · named decision maker and escalation · failure response · residual risk and who accepts it · pilot boundary · TEVV and swap path · review date.

*"A blank field is a no."*

### 06 · Disclosure and records
**Why it goes wrong:** AI's contribution to client work gets disclosed inconsistently, after the fact.

**The move:** Where AI materially contributes to a deliverable, disclose and record: use case, what AI shaped, who verified against what, assumptions and limitations, the wording used, and where it appears. Draft the disclosure and the record together.

*"Disclose and record at the same time, or neither happens."*

### 07 · Start at Tier 3
**Why it goes wrong:** Teams under-rate consequence and negotiate oversight downward to move fast.

**The move:** Anything consequential starts at Tier 3 — decision support. Move down only with evidence. Move up whenever uncertain.

*"Down is earned. Up is default."*

### 08 · The escalation test
**Why it goes wrong:** Consequence, reversibility and time pressure each get argued away one at a time.

**The move:** Any one high — safety, client, clearance, licence to operate; irreversible; clock forcing a decision before the evidence arrives — escalates the tier. Default up when uncertain.

*"One high is enough."*

---

## OVERSIGHT · Human authority and its evidence

### 09 · The four tiers
**Why it goes wrong:** "Human in the loop" is used for everything from full autonomy to a signature, so nobody knows what oversight is actually required.

**The move:** Tier 1: autonomous, tightly bounded, kill switch. Tier 2: human on the loop with veto authority inside a window. Tier 3: human in the loop — a named decider who sees the primary evidence. Tier 4: human in command — no AI origination, human signs.

*"Name the tier, or 'human oversight' means nothing."*

### 10 · Tier 1 is bounded automation
**Why it goes wrong:** Teams hear "autonomous tier" and imagine scope.

**The move:** Tier 1 is the exception: low consequence, reversible, measurable — or a pre-approved safety interlock with fixed parameters, approved owner and kill switch. Consequential and autonomous with no interlock paperwork? It isn't Tier 1.

*"Tier 1 is an exception with paperwork, not a licence."*

### 11 · What happens on silence
**Why it goes wrong:** Tier 2 fails at the veto window: nobody monitors the monitor, and silence becomes consent.

**The move:** Define the default on silence — act or hold — who watches the window, and the override rate you expect. Report the override rate.

*"Silence is a decision. Design its default."*

### 12 · Evidence by tier
**Why it goes wrong:** Tiers get claimed; evidence doesn't get produced.

**The move:** Tier 1: boundary, error rate, kill switch, logging. Tier 2: override rate, seeded-error tests, reviewer rotation. Tier 3: primary evidence, explicit sign-off, provenance. Tier 4: named decision maker, two-person rule, tamper-evident log.

*"If you cannot produce the evidence, you cannot claim the tier."*

### 13 · The human is not a control
**Why it goes wrong:** A human in the loop defeats itself: automation bias, cognitive offloading, anchoring, skill erosion.

**The move:** Show primary evidence and require a reason to accept. Rotate reviewers and sample unaided judgement. Delay the AI estimate until the human frames the problem. Seed errors and rehearse the manual check.

*"The loop is only a control if the human can still say no."*

### 14 · The red line inventory
**Why it goes wrong:** Red lines live in people's heads as instincts, and the first failure is the first written line.

**The move:** Write the permanent Tier 4 decisions — life-safety direction, client warnings, statutory conclusions, client commitments, classification decisions, employment decisions, autonomous enforcement. Each gets a boundary, an owner, a verification rule, a record and an annual review date. Publish internally.

*"Would you defend this line to a client, a regulator and your own staff?"*

### 15 · Decision rights
**Why it goes wrong:** "The committee will look at it" becomes the answer to everything, and nothing has a decider.

**The move:** One matrix, one accountable name per row: approve a system, approve a use case, approve client data use, change a tier, respond to an incident, grant an exception, change a classification. Committees consult; someone decides.

*"One name per row."*

### 16 · Exceptions are decisions too
**Why it goes wrong:** Exceptions get granted verbally in corridors and become policy by precedent.

**The move:** Every exception records who granted it, what it covers, when it expires, and where it lives. The authority to grant sits with a named role, not a mood.

*"An exception with no expiry is a new policy."*

### 17 · The new-tool gate
**Why it goes wrong:** Staff adopt tools faster than committees meet, so the real policy becomes whatever got there first.

**The move:** A short gate, not a long ban: the four questions, permitted data class, tier, owner, review date. Make the safe path the fast path, and keep the approved list short.

*"If the safe path is slow, the unsafe path is the policy."*

### 18 · The two-person rule
**Why it goes wrong:** Single-signature decisions look efficient until the one signature is wrong, rushed or social-engineered.

**The move:** For the stakes that demand it — per the red lines — two named people verify independently before the decision takes effect, recorded in a tamper-evident log.

*"Some doors open only with two keys."*

---

## DATA · Classification, sovereignty, the paste

### 19 · The four classes
**Why it goes wrong:** "Sensitive" is a mood, not a classification, so every tool decision starts from scratch.

**The move:** Very High: accredited or sovereign environment only — or no AI. High: approved enterprise tenant, client permission where required, redact, human review. Medium: approved enterprise AI, no training on your data. Low: any approved tool — and verify anyway.

*"Name the class before the tool."*

### 20 · The default rule
**Why it gets dodged:** Unclassifiable documents get pasted because a deadline is pressing.

**The move:** Cannot classify, cannot paste. Mixed documents take the highest class present. Unclear documents take the highest plausible class, not the lowest.

*"If you cannot classify it, you cannot paste it."*

### 21 · The paste test
**Why it goes wrong:** Pasting is instant, and the questions it should trigger are not.

**The move:** Five, before the paste: class and handling marker · where it runs — country, provider, tenant, sub-processor · who can see it · kept or used — retention, training, deletion · what is in the metadata.

*"The paste is instant. The questions are quick too."*

### 22 · The sovereignty rule
**Why it goes wrong:** Residency and sovereignty get conflated, and data ends up within reach of process you did not expect.

**The move:** Know where it sits and who can compel access. Sovereignty first, Five Eyes minimum, never opposing jurisdictions. Where the class permits, prefer your own tenant.

*"Residency is where it sits. Sovereignty is who can compel it."*

### 23 · Three scales
**Why it goes wrong:** "Very High" gets said without naming the scale, and the decision inherits the wrong one.

**The move:** Keep them separate: data class — what may go where; use-case risk rating — your approval pathway; oversight tier — human authority and evidence.

*"Do not say 'Very High' without naming the scale."*

### 24 · The metadata in the file
**Why it goes wrong:** The document looks clean. The tracked changes, author fields, comments and headers are not.

**The move:** Strip or check metadata before any document is pasted, attached to a prompt, or uploaded.

*"The file carries more than its words."*

### 25 · The secure sandbox
**Why it goes wrong:** Bans push use onto personal accounts, where none of the controls exist.

**The move:** Enterprise tenant — SSO, no training on your data, logging, retention settings. Data controls — DLP for identifiers, egress monitoring, personal accounts blocked on managed devices. Human controls — a short approved-tool list, a named place to ask, a safe alternative for every legitimate need.

*"A ban is not a control. It is a hope."*

### 26 · Shadow use is a measurement
**Why it goes wrong:** The gap between the register and reality gets assumed to be zero.

**The move:** Ask, survey, check the logs — measure shadow use, then onboard every legitimate need onto the safe path.

*"Measure the gap. Do not assume it away."*

---

## VENDORS · Diligence before and after the signature

### 27 · Ten questions before the demo
**Why it goes wrong:** Demos get scheduled before diligence, and the contract inherits whatever wasn't asked.

**The move:** Training data and opt-out · retention, location, proof of deletion · sub-processors and jurisdictions · human review of your prompts · independent field validation · incident detection and notification · model change and deprecation process · audit, access and swap rights · exit, export, deletion.

*"If the answers are vague, the risk is not vague. It is yours."*

### 28 · TEVV
**Why it goes wrong:** Vendor accuracy claims are marketing wearing a lab coat.

**The move:** Demand independent test, evaluation, verification and validation against field ground truth — your conditions, your data shapes, your error costs.

*"Ask for evidence, not a certification badge."*

### 29 · The model swap
**Why it goes wrong:** The vendor quietly upgrades the model, and the workflow you validated is now running on something else.

**The move:** Contract for it: what changes, what notice, what re-validation — and a swap path that does not change your operating model. Register model versions as they change.

*"If the swap changes your workflow, the vendor owns your operating model."*

### 30 · Exit
**Why it goes wrong:** Exit gets negotiated when entering is fun and forgotten when leaving is hard.

**The move:** Before signature: how you export, in what format, proof of deletion, and what keeps running without them.

*"Sign the exit with the entry."*

### 31 · Retention and deletion
**Why it goes wrong:** "Your data is deleted" and "your data trains our model" are both said by sales, and neither is contractual.

**The move:** Retention periods, deletion proof, and training opt-out enforcement — in the contract, inherited by every sub-processor.

*"Deletion you cannot prove is a story."*

### 32 · Where it runs
**Why it goes wrong:** The tenant answer changes the data answer, and nobody re-asks after procurement.

**The move:** Country, provider, tenant, sub-processors — recorded in the registry at approval and re-checked at every renewal.

*"Every tool is a place. Record the place."*

### 33 · Incidents
**Why it goes wrong:** Nobody learns the vendor's incident process until the firm is the one notifying.

**The move:** How incidents are detected, notified and remediated; what triggers your own duty executive; which client commitments this touches. In writing, before you need it.

*"Learn their incident process before you learn it from an incident."*

### 34 · The registry
**Why it goes wrong:** Approved systems live in a spreadsheet three people can find, and reality has more tools than the register.

**The move:** Every tool: ID and name, one owner, status, tier, data class, vendor and hosting, model version, last review. Aligned to the approved-systems register.

*"The registry is the difference between governing and guessing."*

---

## LEARNING · Registers, reviews, the loop

### 35 · The risk register belongs to AI too
**Why it goes wrong:** AI risk gets a separate register nobody maintains, or hides inside IT risk nobody reads.

**The move:** Add AI risks to the register you already run. Minimum columns: ID, use case, one owner, tier and evidence standard, data class, failure modes — invented detail, egress, automation bias, drift, vendor overclaim — controls, residual rating, review date, status.

*"Add AI to the register you already run."*

### 36 · The brief-back
**Why it goes wrong:** Go-lives proceed on enthusiasm and slideware, and the executive never hears the gaps.

**The move:** Before go-live, the owner briefs back: what it does and does not do, the data it sees at what class, the tier and who decides, what happens when it is wrong, how it is recorded, when it is reviewed.

*"Listen for gaps, not polish."*

### 37 · The after-action review
**Why it goes wrong:** Reviews happen only after incidents — on the loudest one, with blame attached.

**The move:** Blameless, five questions, monthly: what was supposed to happen; what actually happened; why the difference; what works that we keep; what changes, owned by whom, by when. Near misses first.

*"Near misses are the cheapest evidence you will get."*

### 38 · Sampling and drift
**Why it goes wrong:** The system that was validated at go-live is quietly different by quarter's end.

**The move:** Sample decisions against ground truth. Track override and error rates. Review drift on the schedule the registry promises.

*"Trust decays on a schedule. Sample against it."*

### 39 · The 90-day gates
**Why it goes wrong:** Operationalisation plans run to the horizon and slip forever.

**The move:** Day 30: register baseline, class-to-tool rules, safe path live. Day 60: evidence of use and oversight in the priority workflows. Day 90: review, corrective action, next-quarter priorities.

*"Gates at 30, 60, 90 — or the plan is a poster."*

### 40 · Review dates are controls
**Why it goes wrong:** Everything in governance carries a review date, and every review date is honoured in the breach.

**The move:** Every artefact — tier, red line, exception, approval, registry row — carries a review date and an owner for the review. Missed reviews surface at the quarterly executive review, by name.

*"The review date is the smallest control in governance. Miss it, and the rest decays."*

---

**The tools change. Accountability does not.**
