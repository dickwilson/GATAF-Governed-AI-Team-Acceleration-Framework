# GATAF – Governed AI Team Acceleration Framework

> **Status:** Pre-v1 Concept Framework &nbsp;|&nbsp; **License:** Apache 2.0 &nbsp;|&nbsp; **Author:** Richard "Dick" Wilson ([@idothuman](https://github.com/idothuman))

GATAF is an open governance framework designed to help enterprise teams safely integrate AI into their daily workflows by mapping existing work, aligning with corporate policy, and co-creating guardrails that enable transparent human–AI collaboration.

---

## What Is GATAF?

GATAF (Governed AI Team Acceleration Framework) provides a **lightweight, platform-independent governance layer** that sits inside your existing infrastructure. Teams use it to:

- Document and map current work activities, tools, and policies
- Identify where AI can accelerate outcomes
- Co-create operational standards and guardrails
- Run structured human–AI collaboration rituals
- Measure transparency, compliance, and synergy outcomes

**Primary outcome: Human–AI–Team Synergy** — results superior to humans alone, AI alone, or unstructured collaboration.

---

## Why GATAF?

Enterprise AI adoption struggles because:

| Problem | GATAF Response |
|---|---|
| Teams lack operational standards | Layer 3: Team Standards & Guardrails |
| Governance is unclear | Policy Validation Engine |
| AI usage transparency is inconsistent | AI Disclosure Protocol + Principle 4 |
| Policy alignment is difficult | Layer 1: Work Genome Mapping |
| Collaboration patterns are undefined | Layer 4: Implementation Rituals |

---

## Framework Architecture

GATAF is organized into **five core layers** and **three supporting engines**.

```
┌──────────────────────────────────────────────────────┐
│  Layer 5 – Measurement & Feedback                    │
├──────────────────────────────────────────────────────┤
│  Layer 4 – Implementation Rituals                    │
├──────────────────────────────────────────────────────┤
│  Layer 3 – Team Standards & Guardrails               │
├──────────────────────────────────────────────────────┤
│  Layer 2 – Acceleration Opportunity Scan             │
├──────────────────────────────────────────────────────┤
│  Layer 1 – Work Genome Mapping                       │
└──────────────────────────────────────────────────────┘
         ↕ Ideation Intake Engine
         ↕ Emergent Pattern Discovery Engine
         ↕ Policy Validation Engine
```

See [`/docs/gataf-framework-architecture-v1.png`](docs/gataf-framework-architecture-v1.png) for the visual architecture diagram.

For detailed layer descriptions, see [`/framework/layers.md`](framework/layers.md).

---

## Immutable Principles

Nine principles govern this framework. They are non-negotiable and may not be modified without explicit direction from the project owner.

1. **Corporate Policies as Foundation** – All standards derive from corporate policy.
2. **No Invalidation Rule** – Lower-level standards cannot override higher-level policy.
3. **Framework Validation Mandatory** – Major outputs require policy validation.
4. **Transparency** – AI contributions must be explainable in under 30 seconds.
5. **On-Demand Status Determinability** – Status of any work item must be instantly visible.
6. **Inclusive Ideation** – Ideas may be captured via any natural medium.
7. **Emergent Adaptation** – New collaboration patterns are expected and encouraged.
8. **Synergy Pursuit** – Framework design should increase human–AI synergy.
9. **Open Source Intent** – Framework released under Apache 2.0.

Full detail: [`/framework/principles.md`](framework/principles.md)

---

## Repository Structure

```
GATAF-Governed-AI-Team-Acceleration-Framework/
├── README.md
├── INVENTORS_DISCLOSURE.md
├── COPILOT_CONTEXT.md
├── LICENSE
├── NOTICE
├── docs/
│   └── gataf-framework-architecture-v1.png
├── framework/
│   ├── framework-overview.md
│   ├── principles.md
│   └── layers.md
├── templates/
│   ├── work-genome-template.md
│   ├── raw-idea-intake-card.md
│   ├── validation-checklist.md
│   └── team-playbook-template.md
├── playbooks/
│   └── sample-team-playbook.md
└── research/
    └── human-ai-collaboration-notes.md
```

---

## Key Artifacts

| Artifact | Location | Purpose |
|---|---|---|
| Framework Overview | [`/framework/framework-overview.md`](framework/framework-overview.md) | Full narrative description |
| Principles | [`/framework/principles.md`](framework/principles.md) | The nine immutable principles |
| Layers | [`/framework/layers.md`](framework/layers.md) | Five-layer architecture detail |
| Work Genome Template | [`/templates/work-genome-template.md`](templates/work-genome-template.md) | Map team work activities |
| Raw Idea Intake Card | [`/templates/raw-idea-intake-card.md`](templates/raw-idea-intake-card.md) | Capture ideas from any medium |
| Validation Checklist | [`/templates/validation-checklist.md`](templates/validation-checklist.md) | Policy compliance verification |
| Team Playbook Template | [`/templates/team-playbook-template.md`](templates/team-playbook-template.md) | Operational collaboration guide |
| Sample Team Playbook | [`/playbooks/sample-team-playbook.md`](playbooks/sample-team-playbook.md) | Worked example |
| Research Notes | [`/research/human-ai-collaboration-notes.md`](research/human-ai-collaboration-notes.md) | Background research |
| Inventor Disclosure | [`INVENTORS_DISCLOSURE.md`](INVENTORS_DISCLOSURE.md) | Formal authorship record |

---

## Getting Started

1. **Read** [`/framework/framework-overview.md`](framework/framework-overview.md) to understand the full model.
2. **Complete** the [`/templates/work-genome-template.md`](templates/work-genome-template.md) for your team.
3. **Run** the Acceleration Opportunity Scan (see [`/framework/layers.md`](framework/layers.md) – Layer 2).
4. **Draft** your team's guardrails using [`/templates/team-playbook-template.md`](templates/team-playbook-template.md).
5. **Validate** outputs against corporate policy using [`/templates/validation-checklist.md`](templates/validation-checklist.md).

---

## Contributing

Contributions are welcome that:

- Improve framework clarity and accessibility
- Propose new operational templates
- Test real-world team workflows
- Document novel human–AI collaboration patterns

**All contributors must preserve:**
- The nine framework principles
- Policy precedence rules
- Transparency requirements

Please open an issue or pull request. See [`COPILOT_CONTEXT.md`](COPILOT_CONTEXT.md) for AI-assisted contribution guidance.

---

## Inventor Disclosure

This framework was originated by **Richard "Dick" Wilson** ([@idothuman](https://github.com/idothuman)) on March 08, 2026.

See [`INVENTORS_DISCLOSURE.md`](INVENTORS_DISCLOSURE.md) for the formal disclosure.

---

## License

Licensed under the **Apache License, Version 2.0**. See [`LICENSE`](LICENSE) for full terms.

Copyright 2026 Richard Wilson

---

## #aicollaboration — Plan Mode

This repository uses **plan mode** for transparent human–AI collaboration. In plan mode, every planning session explicitly records what the human contributed and what the AI collaborator contributed, before any implementation begins.

**Key documents:**

| Document | Purpose |
|---|---|
| [`PLAN.md`](PLAN.md) | Active collaboration plan — every entry is labelled `human` or `copilot` |
| [`templates/plan-mode-template.md`](templates/plan-mode-template.md) | Reusable template for new plan-mode sessions |

Plan mode satisfies **GATAF Principle 4 (Transparency)**: AI contributions are explainable in under 30 seconds because they are visible and attributed at the point of creation, not reconstructed after the fact.

---

## Attribution

Original framework concept: **Richard "Dick" Wilson** ([@idothuman](https://github.com/idothuman))

AI systems may assist in documentation, drafting, and structure. Human authorship remains primary.

*Framework originator: Richard "Dick" Wilson (`i.Richard('Dick')Wilson.human`)*  
*AI collaborator: GitHub Copilot (`Github.Copilot`)*

See [`NOTICE`](NOTICE) for full attribution details.
