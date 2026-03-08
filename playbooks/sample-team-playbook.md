# Sample Team Playbook – Content Operations Team

**Governed AI Team Acceleration Framework – Sample Playbook**
*Version: Pre-v1 | Author: Richard "Dick" Wilson (@idothuman)*

> **Note:** This is a worked example to illustrate how a real team would complete the Team Playbook Template. Names, tools, and policies are illustrative.

---

## Playbook Header

| Field | Response |
|---|---|
| **Team Name** | Content Operations |
| **Department / Division** | Marketing / Corporate Communications |
| **Framework Owner (human)** | Jordan Lee, Content Operations Lead |
| **Playbook Version** | v1.0 |
| **Date Created** | March 2026 |
| **Last Updated** | March 2026 |
| **Policy Validation Status** | ✅ Validated |
| **Validation Date** | March 2026 |

---

## Section 1: Team Charter & AI Philosophy

### 1.1 Team Mission

The Content Operations team produces, reviews, and distributes internal and external communications, marketing collateral, and documentation across all corporate channels. We are accountable for content quality, brand compliance, and legal review coordination.

### 1.2 Our AI Collaboration Philosophy

We use AI to accelerate first-draft generation, copy editing, and content research, so our human writers and strategists can focus on brand voice, audience judgment, and editorial decisions. AI is a drafting and research assistant — not an author or decision-maker. All AI-generated content is reviewed and owned by a named human team member before publication.

### 1.3 Human–AI Accountability Statement

All content published by this team — regardless of AI involvement in its creation — is the responsibility of the named human owner listed in the disclosure record. AI contributions are tools, not authors.

---

## Section 2: Applicable Corporate Policies

| Policy Name / Code | Governing Body | Key Constraint for AI Use |
|---|---|---|
| Corporate Communications Policy v4.2 | Legal & Compliance | All external communications must be reviewed by Legal before publication |
| Data Handling & Classification Policy | Information Security | Confidential data may not be input to consumer AI tools |
| AI Tool Acceptable Use Policy | IT Governance | Only IT-approved AI tools may be used; list maintained by IT |
| Brand Standards Guide | Brand Team | AI-generated copy must pass brand tone review before use |

---

## Section 3: Approved AI Tools

| Tool Name | Vendor | Approved Uses | Prohibited Uses | Data Classification Allowed | Authorization Source |
|---|---|---|---|---|---|
| GitHub Copilot Chat | Microsoft / GitHub | Documentation drafting, technical writing assistance | Inputting confidential client data | Internal / Public | IT Approved Tool List v2026-Q1 |
| Microsoft Copilot (M365) | Microsoft | Email drafts, document summaries, meeting notes | Legal matters, personnel data | Internal | IT Approved Tool List v2026-Q1 |

---

## Section 4: Work Activity Standards & Guardrails

---

### Guardrail Card: Blog Post Drafting

**Activity Name:** Blog Post Drafting
**AI Classification:** ☐ Strong AI candidate ✅
**Policy Anchor(s):** Corporate Communications Policy v4.2; Brand Standards Guide

**Approved AI Role:**
AI may generate first-draft blog post outlines and initial paragraph content based on a provided brief. AI may suggest headlines, subheadings, and transitions.

**Human Role Requirements:**
- Human provides a structured brief before AI drafting begins
- Human reviews and rewrites AI draft for brand voice and accuracy
- Human subject matter expert reviews any technical claims
- Legal review required before external publication

**Input Guardrails:**
- AI may receive: topic briefs, reference articles (public), brand guidelines
- Off-limits: customer PII, internal financial data, confidential product roadmaps

**Output Guardrails:**
- All AI-generated drafts require human editorial review
- Legal review required before any external publication
- No AI draft may be published without the Level 3 disclosure block

**Disclosure Requirements:**
Full Disclosure Block (Level 3) added to all internally published drafts.
For external publication: disclosure block in internal CMS record only (not displayed publicly), plus Legal sign-off.

**Escalation Triggers:**
- AI generates content that references specific legal, financial, or regulatory claims → escalate to Legal
- AI generates content that appears to reference real individuals in a sensitive manner → escalate to Legal & HR

**Validation Status:** ✅ Validated
**Validation Date:** March 2026

---

### Guardrail Card: Email Drafting (Internal)

**Activity Name:** Internal Email Drafting
**AI Classification:** Moderate AI candidate
**Policy Anchor(s):** Data Handling & Classification Policy; AI Tool Acceptable Use Policy

**Approved AI Role:**
AI may draft internal emails based on bullet-point instructions from the sender. AI may suggest subject lines and improve clarity.

**Human Role Requirements:**
- Human provides topic and key points
- Human reviews draft before sending
- Human is responsible for accuracy of all factual claims

**Input Guardrails:**
- AI may receive: topic instructions, non-confidential context
- Off-limits: personnel matters, compensation discussions, customer PII, legal disputes

**Output Guardrails:**
- Human reads and edits before sending — no AI draft goes out unreviewed
- Level 2 disclosure label in internal draft tracking record

**Escalation Triggers:**
- Content relates to employee performance or HR matters → do not use AI; escalate to HR for guidance

**Validation Status:** ✅ Validated
**Validation Date:** March 2026

---

### Human-Gated Activity: Executive Communications

**Activity Name:** Executive Communications (speeches, board updates, CEO statements)
**Reason for Human Gating:** These outputs carry the authority and personal voice of executives. AI assistance could introduce errors of tone, fact, or attribution that carry significant reputational risk.
**Limited AI Allowed?** No — not at this time. May be revisited after framework maturity review.

---

## Section 5: Implementation Rituals

### Daily
- **AI Disclosure Log Update:** Jordan Lee logs any AI-assisted content produced that day in the team's shared CMS draft record (5 min, end of day)
- **Draft Review Queue:** All AI drafts waiting for human review are visible in the `🟠 Pending Human Review` column in Asana

### Weekly (Tuesdays, 9:30–9:45 AM)
- **Synergy Check-In:** Brief team check — what AI assistance worked well this week? Any new patterns? Any friction?
- **Status Sweep:** Confirm all active content items have current status labels

### Monthly (First Monday, 2:00–3:00 PM)
- **Policy Validation Sweep:** Jordan Lee reviews active guardrails against any corporate policy updates
- **Ideation Review:** Process accumulated Idea Intake Cards from team members

### Quarterly (First week of each quarter)
- **Pattern Discovery Session:** Full team, 2 hours — identify and name any new collaboration patterns observed
- **Framework Health Review:** Is GATAF increasing our synergy? What's not working?

---

## Section 6: Status Labels in Use

This team uses the standard GATAF status labels (see [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md) Section 8) implemented via Asana custom fields.

---

## Section 7: Measurement Commitments

| Metric | How We Track It | Review Frequency | Owner |
|---|---|---|---|
| Transparency Compliance Rate | CMS disclosure log audit | Monthly | Jordan Lee |
| AI Disclosure Completeness | Checklist audit on 10% sample | Monthly | Jordan Lee |
| Policy Validation Pass Rate | Validation log | Quarterly | Jordan Lee |
| Synergy Outcome Score | Team survey (1–5 scale) | Quarterly | Jordan Lee |
| Adoption Velocity | Count of active guardrail cards | Quarterly | Jordan Lee |

---

## Section 8: Team Sign-Off

| Name | Role | Date |
|---|---|---|
| Jordan Lee | Content Operations Lead (Framework Owner) | March 2026 |
| Alex Rivera | Senior Content Writer | March 2026 |
| Morgan Chen | Digital Content Specialist | March 2026 |
| Sam Patel | Content Coordinator | March 2026 |

---

## Lessons Learned (Living Section)

*Updated as the team gains experience. These observations feed into Emergent Pattern Discovery.*

| Date | Observation | Layer Affected | Action Taken |
|---|---|---|---|
| March 2026 | AI-generated blog outlines need human restructuring ~70% of the time — brief quality is the key variable | Layer 3 | Added "Brief Quality Checklist" to drafting guardrail |
| | | | |

---

*Copyright 2026 Richard Wilson. Licensed under Apache 2.0. See [`/NOTICE`](../NOTICE) for attribution.*
