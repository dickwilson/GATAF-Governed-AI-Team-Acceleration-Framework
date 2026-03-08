# GATAF Framework Layers

**Governed AI Team Acceleration Framework**
*Version: Pre-v1 | Author: Richard "Dick" Wilson (@idothuman)*

---

## Overview

GATAF is structured as five sequential but iterative layers, supported by three cross-cutting engines. The layers move a team from *understanding their current work* through to *measuring human–AI synergy outcomes*.

The layers are designed to be:

- **Sequential on first adoption** — teams complete them in order
- **Iterative in practice** — teams cycle back through layers as their context evolves
- **Modular** — teams may begin at any layer if prior work already exists

---

## Layer 1 – Work Genome Mapping

### Purpose
Before AI can be governed, the work it will touch must be understood. Layer 1 creates a comprehensive map of a team's current work — what they do, how they do it, what tools they use, and what policies govern their activities.

### Key Activities
1. **Inventory work activities** — List all significant recurring tasks the team performs
2. **Document inputs and outputs** — For each activity, what goes in and what comes out?
3. **Map tools and systems** — What platforms, software, and data sources are in use?
4. **Identify applicable policies** — Which corporate, regulatory, or security policies apply?
5. **Note pain points** — Where are the bottlenecks, delays, or quality issues?

### Primary Artifact
**Team Work Genome Template** — see [`/templates/work-genome-template.md`](../templates/work-genome-template.md)

### Success Criteria
- Every significant work activity is documented
- Policy anchors are identified for each activity
- The team agrees the map is accurate and complete

### Typical Duration
1–2 working sessions (2–4 hours total) for a team of 5–10

---

## Layer 2 – Acceleration Opportunity Scan

### Purpose
With work mapped, teams identify which activities are strong candidates for AI assistance — and which must remain human-led.

### Key Activities
1. **Apply the acceleration assessment** — For each work activity, score it on AI suitability dimensions
2. **Identify high-value targets** — Tasks that are repetitive, time-consuming, and low-risk are prime candidates
3. **Identify human-gated activities** — Tasks requiring judgment, empathy, legal accountability, or ethical reasoning that must remain primarily human
4. **Prioritize** — Rank opportunities by potential synergy gain vs. governance complexity

### Assessment Dimensions

| Dimension | Low AI Suitability | High AI Suitability |
|---|---|---|
| Repetitiveness | Unique each time | Highly repetitive |
| Rule clarity | Ambiguous / judgment-heavy | Clear, rule-based |
| Policy sensitivity | High compliance risk | Low compliance risk |
| Output stakes | High (e.g., legal, financial) | Low to medium |
| Data availability | Sparse or unstructured | Rich and structured |

### Primary Artifact
**Acceleration Opportunity Assessment** — embedded in the Work Genome Template (Layer 2 section) and the Team Playbook

### Success Criteria
- Each work activity has an acceleration score
- High-priority opportunities are identified and ranked
- Human-gated activities are clearly marked

### Typical Duration
1 working session (2–3 hours) building on Layer 1 output

---

## Layer 3 – Team Standards & Guardrails

### Purpose
Layer 3 is where teams co-create the governance rules that will govern AI's participation in their work. These rules are grounded in corporate policy (Principle 1) and cannot override it (Principle 2).

### Key Activities
1. **Draft acceptable use standards** — For each high-priority activity, define what AI *can* and *cannot* do
2. **Define human review requirements** — What must a human review before AI output is used?
3. **Create AI disclosure rules** — How and when must AI contributions be disclosed?
4. **Define escalation paths** — When does an AI-assisted activity require human escalation?
5. **Validate against policy** — Run all standards through the Policy Validation Checklist

### Guardrail Categories

| Category | Examples |
|---|---|
| **Input guardrails** | What data AI may and may not access |
| **Process guardrails** | How AI is used during work execution |
| **Output guardrails** | What AI outputs require human review before use |
| **Disclosure guardrails** | What must be disclosed about AI involvement |
| **Escalation guardrails** | When to stop and involve a human decision-maker |

### Primary Artifact
**Team Playbook** — see [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md)

### Success Criteria
- Standards exist for all high-priority work activities
- Every standard is anchored to a corporate policy
- All standards have passed Policy Validation
- The team has agreed to and signed off on the guardrails

### Typical Duration
2–3 working sessions (4–6 hours total)

---

## Layer 4 – Implementation Rituals

### Purpose
Standards on paper are not governance. Layer 4 embeds GATAF into the team's operational cadence through regular rituals that make human–AI collaboration structured, visible, and improvable.

### Core Ritual Cadences

#### Daily
- **AI Contribution Review** — Team lead or designated reviewer checks AI-assisted outputs from the previous day for transparency compliance
- **Disclosure Log Update** — Any AI-assisted outputs are logged with a brief description of AI's role

#### Weekly
- **Synergy Check-In** — 15–30 minute team discussion: What worked? What didn't? Any new patterns emerging?
- **Status Review** — Confirm all work items have current, accurate status labels

#### Monthly
- **Policy Validation Sweep** — Review all active AI standards against current corporate policy (policies change; GATAF must adapt)
- **Ideation Review** — Process accumulated ideas from the Ideation Intake Engine

#### Quarterly
- **Pattern Discovery Session** — Identify and name any new collaboration patterns that have emerged
- **Framework Health Review** — Assess whether GATAF is increasing synergy; identify any standards that have become friction rather than governance

### Primary Artifact
**Team Playbook (Rituals Section)** — see [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md)

### Success Criteria
- Rituals are scheduled and attended consistently
- Disclosure log is maintained and accessible
- New patterns are being identified and documented
- Team can demonstrate compliance on demand

### Typical Duration
Ongoing. Initial ritual setup takes 1–2 hours; maintenance is embedded in existing team cadence.

---

## Layer 5 – Measurement & Feedback

### Purpose
What gets measured gets managed. Layer 5 establishes the metrics that demonstrate whether GATAF is working — and feeds insights back into the framework for continuous improvement.

### Core Metrics

| Metric | Definition | Target |
|---|---|---|
| **Transparency Compliance Rate** | % of AI-assisted outputs with complete disclosures | 100% |
| **AI Disclosure Completeness** | % of disclosure fields completed per output | ≥ 95% |
| **Policy Validation Pass Rate** | % of standards that pass Policy Validation on first review | ≥ 90% |
| **Synergy Outcome Score** | Team self-assessment of output quality vs. baseline | Improving trend |
| **Adoption Velocity** | Number of work activities actively using GATAF standards | Increasing trend |
| **Pattern Discovery Rate** | Number of new collaboration patterns identified per quarter | Tracked |
| **Escalation Rate** | % of AI-assisted activities requiring human escalation | Tracked (not targeted) |

### Feedback Loops

```
Measurement → Insights → Framework Updates → Better Standards → Better Outcomes → Measurement
```

1. **Layer 5 → Layer 3:** Metric data informs guardrail refinement
2. **Layer 5 → Layer 4:** Ritual effectiveness data informs cadence adjustments
3. **Layer 5 → Framework:** Aggregate patterns across teams feed into the global GATAF framework

### Primary Artifact
**Measurement Dashboard** (team-maintained, format flexible — spreadsheet, Notion, Jira, etc.)

### Success Criteria
- All core metrics are being tracked at team level
- Monthly reporting is consistent
- At least one framework improvement has been proposed based on measurement data within the first 90 days

---

## The Three Supporting Engines

These engines operate **across all layers** and are not tied to any single layer.

---

### Ideation Intake Engine

**Function:** Ensures no ideas are lost, regardless of how or when they arise.

**Operation:**
- Any team member captures an idea in any format (voice, text, sketch, chat)
- The idea is routed to the team's Idea Backlog using the Raw Idea Intake Card
- Ideas are reviewed monthly and triaged: implement, defer, or close

**Artifact:** [`/templates/raw-idea-intake-card.md`](../templates/raw-idea-intake-card.md)

---

### Emergent Pattern Discovery Engine

**Function:** Detects, names, and documents new human–AI collaboration patterns that emerge from practice.

**Operation:**
- During weekly synergy check-ins, team members flag unusual or effective collaboration moments
- Patterns are described, named, and stored
- Validated patterns are submitted to the GATAF repository as contributions

**Artifact:** Pattern Registry (team-maintained; format flexible)

---

### Policy Validation Engine

**Function:** Ensures all GATAF standards and major outputs comply with corporate governance.

**Operation:**
- Any standard or major output can be submitted for policy validation
- The Policy Validation Checklist is applied
- Pass/fail result is logged with rationale
- Failed validations trigger a revision cycle

**Artifact:** [`/templates/validation-checklist.md`](../templates/validation-checklist.md)

---

## Layer Interaction Summary

```
[Layer 1: Work Genome]
        ↓
[Layer 2: Opportunity Scan]
        ↓
[Layer 3: Standards & Guardrails] ←──────────────────────────┐
        ↓                                                      │
[Layer 4: Implementation Rituals]                             │
        ↓                                                      │
[Layer 5: Measurement & Feedback] ─── insights feed back ────┘
        ↑
[Supporting Engines operate across all layers continuously]
```

---

*Copyright 2026 Richard Wilson. Licensed under Apache 2.0. See [`/NOTICE`](../NOTICE) for attribution.*
