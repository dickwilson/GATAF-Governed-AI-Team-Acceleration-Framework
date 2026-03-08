# GATAF Immutable Principles

> These nine principles are **non-negotiable**. They form the governance foundation of GATAF and take precedence over all team-level standards, operational decisions, and framework adaptations. No principle may be removed or overridden without explicit direction from the framework originator.

---

## Principle 1: Corporate Policies as Foundation

> *All standards must derive from corporate policy.*

GATAF operates within — not above — the governance structures of the organization adopting it. Every team standard, guardrail, and collaboration pattern defined through GATAF must be traceable to an applicable corporate policy. If a conflict arises between a GATAF-derived standard and corporate policy, corporate policy prevails.

**Implication for teams:** Before defining any team-level AI standard, identify the relevant corporate policies that govern the domain (data handling, AI use, intellectual property, confidentiality, etc.).

---

## Principle 2: No Invalidation Rule

> *Lower-level standards cannot override higher-level policy.*

A team-level standard created through the GATAF framework may be more specific, more restrictive, or more operationally detailed than a corporate policy — but it may never contradict, relax, or nullify it. This creates a strict policy hierarchy.

**Implication for teams:** Team standards may add constraints beyond corporate policy. They may not remove constraints that corporate policy imposes.

---

## Principle 3: Framework Validation Mandatory

> *Major outputs require policy validation.*

Any significant artifact produced through GATAF — including team standards documents, team playbooks, acceleration opportunity assessments, and AI disclosure protocols — must be validated against applicable corporate policy before adoption. Validation is not optional.

**Implication for teams:** Include a policy validation step in your approval workflow for all major GATAF outputs. Use the [`/templates/validation-checklist.md`](../templates/validation-checklist.md) to guide this process.

---

## Principle 4: Transparency

> *AI contributions must be explainable in under 30 seconds.*

Any work product that involved AI assistance must be disclosable in a clear, brief, and understandable way. If a team member cannot explain AI's role in a given output within 30 seconds, the transparency standard has not been met.

**Implication for teams:** Every workflow that involves AI must include an AI disclosure step. AI contributions should be documented at the point of creation, not reconstructed after the fact.

---

## Principle 5: On-Demand Status Determinability

> *The status of any work item must be instantly visible.*

At any moment, any authorized stakeholder should be able to determine the status of any work item — including its current stage, who is responsible, and whether AI was involved. Ambiguity about work status is a governance failure.

**Implication for teams:** Use status labels, metadata, and tracking practices that make work state immediately legible without requiring investigation or follow-up.

---

## Principle 6: Inclusive Ideation

> *Ideas may be captured via any natural medium.*

The framework must not impose barriers to idea contribution. Team members should be able to submit ideas, concerns, observations, and insights through whatever natural medium works for them — voice notes, handwritten sketches, casual conversation, structured templates, or direct AI interaction. The medium is not the constraint; capture and integration are.

**Implication for teams:** Implement an Ideation Intake Engine that accepts multiple input formats. No idea should be lost because the format did not match a template.

---

## Principle 7: Emergent Adaptation

> *New collaboration patterns are expected and encouraged.*

GATAF does not assume that the framework will remain static. Human–AI collaboration will evolve, new patterns will emerge organically, and the framework must accommodate and capture this evolution. Teams are expected to surface new patterns and contribute them back to the framework.

**Implication for teams:** Build in regular retrospectives to identify emerging collaboration patterns. Use the Emergent Pattern Discovery Engine to document and evaluate them.

---

## Principle 8: Synergy Pursuit

> *Framework design should increase human–AI synergy.*

Every decision made about GATAF's design, templates, rituals, and standards should be evaluated against this question: *Does this increase the synergy between humans and AI on this team?* Features, requirements, or constraints that reduce synergy without a compelling governance reason should be challenged.

**Implication for teams:** Use synergy as a lens when evaluating framework adaptations. Bureaucracy for its own sake violates this principle.

---

## Principle 9: Open Source Intent

> *The framework will be released under Apache 2.0.*

GATAF is designed from its origin to be openly shared, freely adapted, and collaboratively improved. All GATAF documentation, templates, and framework artifacts are released under the Apache License, Version 2.0. This principle reflects a commitment to the commons and to the belief that open governance standards benefit all.

**Implication for contributors:** Contributions to this repository are made under the terms of the Apache 2.0 license. Attribution is preserved via the [`NOTICE`](../NOTICE) file.

---

## Summary Table

| # | Principle | Core Requirement |
|---|-----------|-----------------|
| 1 | Corporate Policies as Foundation | All standards trace to corporate policy |
| 2 | No Invalidation Rule | Lower standards may not override higher policy |
| 3 | Framework Validation Mandatory | Major outputs require policy validation |
| 4 | Transparency | AI contributions explainable in <30 seconds |
| 5 | On-Demand Status Determinability | Work status must be instantly visible |
| 6 | Inclusive Ideation | Ideas accepted in any natural medium |
| 7 | Emergent Adaptation | New collaboration patterns are expected |
| 8 | Synergy Pursuit | Design must increase human–AI synergy |
| 9 | Open Source Intent | Released under Apache 2.0 |

---

*Part of the GATAF – Governed AI Team Acceleration Framework*
*Licensed under Apache 2.0 | Originated by Richard "Dick" Wilson (@idothuman)*
