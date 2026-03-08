# GATAF Framework Layers

> Detailed definitions for each of the five core layers of the Governed AI Team Acceleration Framework, including their purpose, inputs, activities, outputs, and connections to adjacent layers.

---

## Overview

GATAF's five layers represent a progressive journey from **understanding current work** to **measuring improved outcomes**. Each layer produces artifacts that feed into the next, creating a coherent and traceable governance chain.

```
┌─────────────────────────────────────────────────────┐
│  Layer 5: Measurement & Feedback                    │
│  ↑ feeds back to improve all earlier layers         │
├─────────────────────────────────────────────────────┤
│  Layer 4: Implementation Rituals                    │
│  ↑ applies the standards from Layer 3               │
├─────────────────────────────────────────────────────┤
│  Layer 3: Team Standards & Guardrails               │
│  ↑ governs the opportunities from Layer 2           │
├─────────────────────────────────────────────────────┤
│  Layer 2: Acceleration Opportunity Scan             │
│  ↑ analyzes the genome from Layer 1                 │
├─────────────────────────────────────────────────────┤
│  Layer 1: Work Genome Mapping                       │
│  Foundation: documents current work                 │
└─────────────────────────────────────────────────────┘
```

---

## Layer 1 – Work Genome Mapping

### Purpose

Establish a complete, structured picture of the team's current work — what they do, how they do it, what tools and inputs they use, and what policies govern their outputs. This baseline is the "Work Genome" from which all AI acceleration is measured.

### Why This Matters

You cannot govern what you have not mapped. Without a documented Work Genome, teams cannot systematically identify AI opportunities, define appropriate guardrails, or measure synergy improvement.

### Key Activities

- Inventory all recurring work tasks and workflows
- Document inputs, outputs, and tools for each task
- Identify applicable corporate policies for each work area
- Note current pain points, bottlenecks, and quality risks
- Capture existing informal AI use (shadow AI)

### Primary Artifact

**Team Work Genome** → [`/templates/work-genome-template.md`](../templates/work-genome-template.md)

### Outputs to Layer 2

- Prioritized list of work areas to analyze
- Policy constraints mapped to each work area
- Identified complexity and volume patterns

---

## Layer 2 – Acceleration Opportunity Scan

### Purpose

Analyze the Work Genome to identify specific tasks and workflows that are strong candidates for AI assistance. Evaluate each candidate for AI suitability, policy compatibility, and implementation risk.

### Why This Matters

Not all tasks benefit from AI assistance. Some tasks require human judgment that AI cannot replicate. Others may involve data that cannot be processed by AI under corporate policy. The scan creates a governed, prioritized shortlist of legitimate acceleration opportunities.

### Key Activities

- Review Work Genome for task patterns suitable for AI
- Evaluate each candidate task against AI capability dimensions
- Assess data sensitivity and policy constraints
- Rate feasibility, risk, and expected synergy gain
- Prioritize opportunities by value and compliance readiness

### Evaluation Dimensions

| Dimension | Description |
|-----------|-------------|
| AI Suitability | Does AI meaningfully improve this task? |
| Policy Compatibility | Does applicable policy permit AI use here? |
| Data Risk | What data sensitivity issues exist? |
| Human Review Requirement | What level of human oversight is needed? |
| Estimated Synergy Gain | What improvement is expected? |

### Primary Artifact

**Acceleration Opportunity Assessment** (based on Work Genome analysis)

### Outputs to Layer 3

- Approved list of AI-assisted workflows
- Risk ratings per workflow
- Policy constraints to be encoded as guardrails

---

## Layer 3 – Team Standards & Guardrails

### Purpose

Define the governance rules that bound AI use for the team. These standards translate corporate policy and acceleration opportunity findings into specific, actionable behavioral expectations for how AI is used, disclosed, reviewed, and documented.

### Why This Matters

Without standards, AI use becomes inconsistent, undocumented, and ungovernable. Layer 3 creates the team's operational constitution for human–AI collaboration.

### Key Activities

- Define AI disclosure requirements for each workflow
- Set quality thresholds and human review requirements
- Establish escalation paths for AI output uncertainty
- Create a Status Label Metadata System for work tracking
- Validate all standards against corporate policy (Policy Validation Engine)
- Document standards in the Team Playbook

### Standard Categories

| Category | Examples |
|----------|---------|
| Disclosure Standards | When and how AI contribution must be declared |
| Quality Standards | Minimum review requirements before publication |
| Data Standards | What data may or may not be processed by AI |
| Escalation Standards | When AI output must be reviewed by a human expert |
| Documentation Standards | How AI use is recorded in the work record |

### Primary Artifact

**Team Standards section of Team Playbook** → [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md)

### Outputs to Layer 4

- Defined AI use behaviors for each approved workflow
- Disclosure templates and protocols
- Review and escalation procedures

---

## Layer 4 – Implementation Rituals

### Purpose

Establish the recurring operational patterns — daily, weekly, and monthly — that keep human–AI collaboration visible, consistent, improvable, and policy-compliant. Rituals operationalize the standards defined in Layer 3.

### Why This Matters

Governance documents without operational habits produce no real change. Layer 4 turns the team's standards into living practice through regular, structured collaboration patterns.

### Key Ritual Types

#### Daily Rituals
- **AI Contribution Check-in** – Brief acknowledgment of AI-assisted work in progress
- **Status Label Updates** – Ensuring all work items reflect current status
- **Idea Capture** – Submitting emerging ideas to the Ideation Intake Engine

#### Weekly Rituals
- **Synergy Review** – Team review of human–AI collaboration outcomes for the week
- **Transparency Audit** – Spot-check that AI disclosures are complete and accurate
- **Pattern Surface** – Share any new collaboration patterns observed

#### Monthly Rituals
- **Governance Retrospective** – Review standards and guardrails for continued relevance
- **Playbook Update** – Incorporate learnings and new patterns into the Team Playbook
- **Metrics Review** – Analyze Layer 5 data and adjust practices accordingly

### Primary Artifact

**Implementation Rituals section of Team Playbook** → [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md)

### Outputs to Layer 5

- Activity data for measurement
- Compliance events and exceptions
- Emerging patterns for discovery engine

---

## Layer 5 – Measurement & Feedback

### Purpose

Track, analyze, and report on the outcomes of GATAF implementation. Provide data that confirms governance compliance, measures synergy gains, surfaces adoption health, and identifies improvements to feed back into earlier layers.

### Why This Matters

Without measurement, GATAF cannot demonstrate value, cannot improve, and cannot sustain stakeholder confidence. Layer 5 closes the governance loop and enables the framework to evolve.

### Key Metrics Categories

#### Transparency Compliance
- Percentage of AI-assisted outputs with complete disclosures
- Average time to disclose AI contribution
- Disclosure quality rating (complete, partial, missing)

#### Synergy Outcomes
- Before/after quality comparison for AI-assisted workflows
- Cycle time improvement
- Human review reversal rate (outputs changed after human review)
- Team satisfaction with AI collaboration

#### Adoption Health
- Percentage of approved AI workflows actively in use
- Idea submission rate through the Ideation Intake Engine
- New collaboration pattern discovery rate

#### Governance Adherence
- Policy validation completion rate
- Escalation event frequency
- Standards deviation incidents

### Feedback Loops

| Observation | Feeds Back To |
|-------------|---------------|
| Low transparency compliance | Layer 3 (strengthen disclosure standards) |
| New collaboration patterns | Layer 3 (add new guardrails) and Layer 4 (add new rituals) |
| Workflow performing poorly | Layer 2 (re-evaluate opportunity) |
| New corporate policy | Layer 1 (re-validate Work Genome) |

### Primary Artifact

**Measurement Dashboard / Metrics Report** (team-defined format)

---

## Supporting Engines

Three engines operate across all five layers:

### Ideation Intake Engine

Accepts raw ideas from team members in any format and routes them to the appropriate layer or backlog for consideration. Ensures that observations, concerns, and insights are captured without friction.

See [`/templates/raw-idea-intake-card.md`](../templates/raw-idea-intake-card.md) for the primary intake artifact.

### Emergent Pattern Discovery Engine

Monitors team behavior, ritual outputs, and measurement data to identify new human–AI collaboration patterns that arise organically. Documents and evaluates patterns for potential incorporation into the framework.

### Policy Validation Engine

Provides a structured process for validating framework artifacts against corporate policy. Called upon at key transition points between layers — particularly at Layer 3 (standards creation) and whenever major artifacts are finalized.

See [`/templates/validation-checklist.md`](../templates/validation-checklist.md) for the validation process.

---

*Part of the GATAF – Governed AI Team Acceleration Framework*
*Licensed under Apache 2.0 | Originated by Richard "Dick" Wilson (@idothuman)*
