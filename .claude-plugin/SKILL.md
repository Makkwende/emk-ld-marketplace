---
name: emk-ld-workflow
description: "Analyze L&D, instructional design, training, talent development, onboarding, leadership development, and performance requests and turn them into structured project workflows with tasks, deliverables, dependencies, human review checkpoints, risks, and recommended next actions."
---

# EMK L&D Project Workflow Skill

Use this skill whenever a user asks to:
- plan an L&D project
- create a training project workflow
- analyze a training request
- develop onboarding
- design a learning program
- review an instructional design project
- identify missing L&D project steps
- evaluate an L&D project plan
- create a learning-development timeline
- determine project dependencies
- identify project risks
- review an L&D workflow
- determine where stakeholder or SME review should occur

## CONTEXT ASSUMPTIONS

Do not assume the user works for EMK Learning Solutions or has access to EMK programs, materials, templates, or resources unless that information is explicitly provided in the current project context. Treat the user as an independent L&D professional working on their own project unless told otherwise.

---

## STEP 1 — CAPTURE THE PROJECT REQUEST

Extract available information about:
- Business/performance need
- Audience
- Current situation
- Desired performance
- Desired outcome
- Project scope
- Timeline
- Delivery modality
- Stakeholders
- Sponsor
- SMEs
- Existing content/resources
- Learning technology
- Accessibility requirements
- Evaluation expectations
- Budget/resource constraints
- Approval requirements

Do not ask the user for information already supplied.

---

## STEP 2 — CLARIFICATION GATE: CHECK FOR CRITICAL GAPS BEFORE BUILDING

Do not generate a complete project workflow immediately after receiving only a general business or performance problem.

Before creating the full workflow, determine whether you understand at minimum:
1. The business or performance problem.
2. The desired behavior or performance change (the outcome stated in concrete, ideally observable terms — not just "employees struggle with X").
3. Enough about the current state, existing support, resources, or constraints to avoid designing a solution based primarily on assumptions.

When one of these three critical areas is missing, ask the next highest-value question before generating the full workflow. Do not skip straight to a full build with assumptions noted — ask first.

Ask questions one at a time, or in a small group of no more than 2–3 when the questions are closely related. Do not front-load a long, generic intake questionnaire, and do not bundle unrelated questions (e.g., business need + delivery modality + stakeholders) into one large batch — work through the critical areas above first, then move to secondary details (stakeholders, existing content, technology, accessibility, budget) only once the three critical areas are addressed, still in small groups.

If the desired performance outcome is still materially undefined after the user's answers, ask one concise outcome question before finalizing detailed learning objectives or curriculum topics. Do not infer a specific measurable outcome on the user's behalf when one concise question would settle it.

Do not create detailed learning topics, modalities, deliverables, or recommended solutions before the user's answers support those recommendations. Proposing specific content or solutions too early anchors the user on a direction that may not fit the actual need.

If the user explicitly asks you to proceed without providing the missing information, create a preliminary workflow and clearly label all assumptions throughout the output (not only in a single assumptions section — mark each assumed field inline as well).

A "READY WITH ASSUMPTIONS" classification is not a reason to skip information that would be easy to obtain and would materially improve the project design. Reserve that classification for information that is genuinely hard to get quickly (e.g., a sponsor who is unavailable this week) — not for gaps you could have resolved by asking one more question.

---

## STEP 3 — CONFIRM SCOPE: CONFIRMED VS. POSSIBLE-NEEDS-TO-VALIDATE BEHAVIORS

When the user identifies one specific performance behavior or gap (e.g., "delegation" as the target behavior), treat only that behavior as confirmed project scope.

Do not automatically convert related or commonly associated behaviors into project requirements, learning objectives, topics, or deliverables — even when they are typically bundled with the confirmed behavior in standard curricula (for example, do not assume feedback skills or managing-former-peers content belong in the project just because they commonly accompany delegation in a management-transition program).

Related or commonly associated behaviors may be surfaced as **"possible needs to validate"** — a distinct, clearly labeled category from confirmed scope. List them separately from the confirmed workflow content.

Before building detailed learning content (objectives, curriculum, session design, deliverables) around any of those additional behaviors, either:
- ask the user to explicitly confirm them as in-scope, or
- recommend that they be validated during needs analysis before being added to the project.

Do not build out full learning design, development tasks, or deliverables for anything sitting in the "possible needs to validate" list. If the project uses a phased approach (see Step 10), unconfirmed behaviors belong in a later wave, gated by validation — not folded into the current wave's design.

---

## STEP 4 — DETERMINE WHETHER LEARNING IS LIKELY TO ADDRESS THE NEED

Do not assume a request for training proves a training problem exists.

Do not infer that training is the appropriate primary solution simply because the performance problem is commonly or typically addressed through training (e.g., new-manager transitions, onboarding, compliance topics). Continue examining whether knowledge or skill is actually contributing to the problem, even for topics that are conventionally treated as training issues.

Consider whether the apparent performance problem could involve:
- knowledge
- skill
- unclear expectations
- inadequate tools
- inefficient processes
- workload/capacity
- incentives
- feedback
- management
- organizational barriers
- technology
- environmental factors

Do not make unsupported diagnoses.
If necessary, recommend further performance analysis.

---

## STEP 5 — ASSIGN A READINESS CLASSIFICATION

Use one or more:

### READY TO PLAN
Enough information exists to create a reasonable workflow.

### READY WITH ASSUMPTIONS
Enough information exists to create a preliminary workflow, but assumptions must be documented. Use only after the Step 2 clarification gate has been applied — not as a shortcut around it.

### NEEDS ADDITIONAL ANALYSIS
The underlying need is insufficiently defined or learning may not be the correct primary solution.

### HIGH-RISK TIMELINE OR SCOPE
Timeline, scope, resources, dependencies, or review requirements create significant project risk.

Explain the classification briefly.

---

## STEP 6 — CREATE THE PROJECT WORKFLOW

Select only phases relevant to the project, and build detailed tasks/deliverables only for confirmed scope (see Step 3) — not for anything still in the "possible needs to validate" list.

Possible phases include:

### Discovery & Analysis
Tasks may include:
- clarify business need
- performance analysis
- audience analysis
- stakeholder interviews
- SME interviews
- existing-content review
- resource review
- technology analysis
- constraints analysis
- success measures

### Project Alignment & Planning
Tasks may include:
- confirm scope
- establish roles
- establish timeline
- identify dependencies
- establish communication
- establish review cycles
- identify risks
- confirm technology
- confirm accessibility expectations

### Learning Design
Tasks may include:
- create measurable objectives
- determine learning strategy
- determine modality
- create curriculum architecture
- sequence learning
- create practice/application strategy
- create assessment strategy
- plan evaluation

### Development
Tasks may include:
- prototypes
- storyboards
- eLearning
- facilitator guides
- participant materials
- job aids
- assessments
- videos
- performance support
- platform configuration

Recommend only applicable deliverables.

### Review & Quality Assurance
Possible reviews include:
- instructional design
- SME
- stakeholder
- accessibility
- content accuracy
- technical QA
- proofreading
- learner testing
- pilot testing
- final approval

Quality review should occur throughout the workflow, not only at the end.

### Implementation
Tasks may include:
- facilitator preparation
- learner communications
- LMS configuration
- publishing
- train-the-trainer
- launch
- delivery
- learner support

### Evaluation & Improvement
Tasks may include:
- reaction
- learning
- application
- behavior
- relevant performance measures
- stakeholder feedback
- improvement recommendations
- material updates
- lessons learned

---

## STEP 7 — IDENTIFY DEPENDENCIES

For every major task, consider:
- What must happen before this?
- What does this task enable?
- Can it occur concurrently with another task?
- Does another person need to review or approve it?

Do not make every project phase unnecessarily sequential.

When useful (e.g., a tight timeline, a multi-workstream build, or the user asks), separate this into two explicit lists in the output: what can happen concurrently, and which tasks are critical dependencies that cannot be parallelized. Note when "concurrent" workstreams still share the same limited people/capacity — concurrent tasks are not free of resource risk just because they aren't sequential.

---

## STEP 8 — IDENTIFY HUMAN CHECKPOINTS

Recommend checkpoints only where useful.

Potential reviewers include:
- practitioner
- project manager
- L&D manager
- senior L&D leader
- SME
- sponsor
- stakeholder
- client
- accessibility reviewer
- technical reviewer
- quality reviewer
- compliance/legal reviewer when applicable

For every checkpoint indicate:
- WHO
- WHAT
- REVIEW or APPROVAL
- WHY it matters

When useful (e.g., the user asks, or the project has several checkpoints), present this as a table so review items and approval items are easy to tell apart at a glance.

---

## STEP 9 — ASSESS PROJECT RISK

Check for:
- unclear business need
- unclear performance outcome
- training selected prematurely
- unrealistic timeline
- excessive scope
- missing stakeholder
- missing SME
- content not available
- objectives not measurable
- development occurring prematurely
- insufficient SME review
- insufficient stakeholder review
- accessibility planned too late
- evaluation missing
- technology not tested
- insufficient QA
- unclear decision authority
- insufficient approval time
- dependencies missing from schedule

For significant risks, provide a practical mitigation.
Do not state that a project will fail.

When the user asks for a short list (e.g., "top 3 risks"), rank by actual impact on the launch date or outcome rather than listing every possible risk.

---

## STEP 10 — HANDLE TIGHT TIMELINES

Never simply compress every project activity to make an unrealistic deadline appear feasible.

When timeline and scope conflict, provide options such as:

### OPTION A — MAINTAIN DEADLINE
Reduce scope, simplify modality, reuse existing content, or prioritize critical learning.

### OPTION B — MAINTAIN SCOPE
Adjust the launch date.

### OPTION C — PHASED DELIVERY
Deliver the highest-priority solution first and develop remaining components later. Pair this with Step 3: the first wave should cover only confirmed scope; anything in "possible needs to validate" belongs in a later wave, gated by actual validation.

Clearly identify resulting tradeoffs.

---

## STEP 11 — PRODUCE THE OUTPUT

Only produce this full output once the Step 2 clarification gate is satisfied (either the three critical areas are known, or the user has explicitly asked to proceed on assumptions) and Step 3 scope has been confirmed.

Default output:

# L&D Project Snapshot
**Project:**  
**Business/Performance Need:**  
**Audience:**  
**Desired Outcome:**  
**Timeline:**  
**Delivery Approach:**  
**Key Stakeholders:**

Use "Not yet defined" rather than inventing information. Mark any assumed value inline (e.g., "Blended — *assumed*").

# Readiness Assessment
State classification and provide a concise rationale. Note the phased approach if one is in use.

# Recommended Project Workflow
| Phase | Key Tasks | Deliverable/Output | Owner or Reviewer | Dependency/Checkpoint |
|---|---|---|---|---|

Build this only for confirmed scope (Step 3).

# Key Review & Approval Points
Identify significant human checkpoints (table format when there are several — see Step 8).

# Missing Information
Identify information that remains unresolved.

# Possible Needs to Validate
List related/commonly associated behaviors or topics that are NOT part of confirmed scope, and how they should be validated (needs analysis, user confirmation) before being added to a future wave.

# Project Risks
Identify important risks and practical mitigations.

# Recommended Next Actions
Provide approximately 3–5 immediate next actions.

## Optional: Expanded Execution View
Include this section when the timeline is tight, the project has multiple workstreams, or the user asks for it. It contains:
- **What can happen concurrently** — plain list, noting shared-capacity caveats
- **Critical dependencies** — the tasks that cannot be parallelized, in order
- **Review vs. Approval** — table format (Item / Type / Who)
- **Top risks to the launch** — a short, ranked list (e.g., top 3) rather than the full risk register
- **First N business days** — a concrete day-by-day list of what should happen immediately, sized to however many days the user needs covered

---

## EXPERIENCE ADAPTATION

If the user is new to L&D:
Provide additional explanation and rationale.

If the user is experienced:
Be concise and focus on workflow, decisions, risks, dependencies, and quality.

If the user is an L&D manager:
Emphasize review, quality, coaching, governance, workload, and approval.

If the user is a senior leader:
Emphasize portfolio visibility, consistency, standards, risk, governance, resources, and decision points.

---

## HUMAN OVERSIGHT

Recommendations support but do not replace professional judgment.
Always distinguish assumptions from facts.
The user has authority to modify, reject, or override recommendations.