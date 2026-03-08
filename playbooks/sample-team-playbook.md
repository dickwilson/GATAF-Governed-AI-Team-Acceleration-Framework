# Sample Team Playbook: Content & Communications Team

> **GATAF Playbook Example**
>
> This sample playbook demonstrates a completed Team Playbook for a fictional Content & Communications team. Use it as a reference when building your own playbook using [`/templates/team-playbook-template.md`](../templates/team-playbook-template.md).

---

## Playbook Header

| Field | Value |
|-------|-------|
| **Team Name** | Content & Communications Team |
| **Department / Business Unit** | Corporate Marketing |
| **Playbook Version** | v1.0 |
| **Effective Date** | 2026-04-01 |
| **Last Reviewed** | 2026-04-01 |
| **Next Review Due** | 2026-07-01 |
| **Playbook Owner** | Jordan Lee, Content Strategy Lead |
| **Policy Validated** | ✅ Yes — Date: 2026-03-28 |

---

## Part 1: Team Context

### 1.1 Team Purpose

The Content & Communications team creates, manages, and distributes internal and external content for the organization. This includes executive communications, marketing copy, internal newsletters, social media content, and product documentation. The team is accountable for brand voice consistency, policy compliance in all published materials, and timely delivery of communications.

### 1.2 Key Stakeholders

| Stakeholder | Role / Relationship |
|-------------|---------------------|
| CMO | Executive sponsor; approves major communications |
| Legal & Compliance | Reviews external content and policy-sensitive materials |
| Product Management | Provides input for product-related content |
| HR | Partners on internal communications |
| IT Security | Reviews AI tool approvals and data handling |

### 1.3 Corporate Policy References

| Policy Name / Document | Owner / Source | Key Relevance |
|-----------------------|----------------|---------------|
| AI Use Policy v2.1 | IT Governance | Approved AI tools, prohibited use cases |
| Data Classification Policy v3.0 | Information Security | What data may be used with AI tools |
| Content & Brand Standards | Marketing Ops | Brand voice, approval workflows |
| Employee Communications Policy | HR | Internal communication requirements |
| Intellectual Property Policy | Legal | AI-generated content ownership |

---

## Part 2: GATAF Commitment

### 2.1 Framework Adoption Statement

The Content & Communications Team commits to operating under the Governed AI Team Acceleration Framework (GATAF) in alignment with the nine immutable principles. This playbook documents our implementation of that commitment.

### 2.2 Principle Acknowledgment

By adopting this playbook, the team acknowledges and accepts all nine GATAF principles as binding constraints on team-level AI standards. All team members have reviewed [`/framework/principles.md`](../framework/principles.md).

### 2.3 Human Accountability Statement

All AI-assisted outputs produced by this team are the responsibility of a named human team member. Every published piece of content has a human author of record, regardless of AI involvement in drafting.

---

## Part 3: Approved AI Use

### 3.1 Approved AI Tools

| Tool | Approved For | Data Sensitivity Permitted | Human Review Required? |
|------|-------------|---------------------------|----------------------|
| Microsoft Copilot (M365) | Drafting, editing, summarization | Internal and below | ✅ Always |
| Grammarly Business | Grammar, clarity, tone checking | Internal and below | ✅ When flagged |
| Adobe Firefly | Image generation for approved campaigns | Public information only | ✅ Always (brand review) |

### 3.2 Prohibited AI Use

- Processing customer data, PII, or confidential business information in external AI tools not approved by IT
- Using AI to generate final published content without human authorship review
- Using AI tools to create communications that will be attributed to a named executive without that executive's review and approval
- Using unapproved AI tools, browser extensions, or consumer AI products for work tasks

---

## Part 4: AI Disclosure Protocol

### 4.1 Disclosure Standard

All team outputs that involved AI assistance include a disclosure that meets the GATAF 30-Second Transparency Standard.

### 4.2 Disclosure Method

✅ **Metadata tag** – AI involvement recorded in the work item's status label in our project management tool (Asana)
✅ **Document header** – AI disclosure header on internal documents
✅ **Inline notation** – Brief note in document review comments when AI drafted a section

### 4.3 Disclosure Template

**For internal documents:**
```
AI Assistance Disclosure:
Portions of this document were drafted with AI assistance (Microsoft Copilot).
Human author of record: [Name]
Reviewed and approved by: [Reviewer name]
Date finalized: [YYYY-MM-DD]
```

**For external/published content (internal record only):**
```
Content Production Note [Internal Use]:
AI tool(s) used: [tool name(s)]
AI contribution: [e.g., "First draft generated; substantially revised by author"]
Human author of record: [Name]
Final approval: [Approver name and date]
```

### 4.4 Disclosure Exemptions

Brief AI-assisted grammar or spell-check corrections (Grammarly) do not require disclosure beyond the work item metadata tag.

---

## Part 5: Quality Standards

### 5.1 Review Requirements by Output Type

| Output Type | Required Review Steps | Reviewer Role |
|-------------|----------------------|---------------|
| Executive communications | Full read-through, fact-check, executive review | Content Lead + Executive |
| External press / marketing copy | Brand review, Legal review for claims, final approval | Content Lead + Legal |
| Internal newsletter | Author review, spot-check for accuracy | Author + Content Lead |
| Social media posts | Author review + team approval for sensitive topics | Author + Content Lead |
| Product documentation | Technical accuracy review + editorial review | Author + Product PM |
| Internal operational emails | Author review | Author |

### 5.2 Escalation Triggers

- AI-drafted content contains factual claims about products, financials, or legal matters → Escalate to subject matter expert before use
- AI-drafted executive communication will be published under a named executive's byline → Executive review required (no exceptions)
- AI-generated image to be used in external campaign → Brand + Legal review required
- Any AI output that the author is uncertain about factually → Hold for human verification; do not publish

---

## Part 6: Implementation Rituals

### 6.1 Daily Rituals

| Ritual | Description | Owner | Time Required |
|--------|-------------|-------|--------------|
| AI Contribution Check-in | During daily stand-up, each team member flags any work that involved AI assistance | Team | 2–3 min |
| Status Label Updates | All work items in Asana updated before end of day | Each team member | 5 min |
| Idea Capture | Observations about AI use submitted to #content-ai-ideas Slack channel | Anyone | As needed |

### 6.2 Weekly Rituals

| Ritual | Description | Owner | Cadence |
|--------|-------------|-------|---------|
| Synergy Review | 15-min Friday review of what worked and what didn't in human–AI collaboration | Jordan Lee | Every Friday |
| Transparency Audit | Spot-check 2–3 completed work items to confirm disclosures are present and accurate | Jordan Lee | Every Monday |
| Pattern Surface | Slack thread: "What new AI collaboration patterns did you notice this week?" | Team | Every Thursday |

### 6.3 Monthly Rituals

| Ritual | Description | Owner | Cadence |
|--------|-------------|-------|---------|
| Governance Retrospective | 30-min team review of playbook relevance and any policy changes | Jordan Lee | First Monday of month |
| Playbook Update | Incorporate retrospective findings into this document | Jordan Lee | Within 1 week of retrospective |
| Metrics Review | Review AI disclosure compliance, synergy scores, and idea submission rates | Jordan Lee | Last Friday of month |

---

## Part 7: Status Label System

| Label | Meaning | Used For |
|-------|---------|---------|
| `🔵 In Progress` | Work is actively being done | Any active work item |
| `🤖 AI Drafting` | AI is generating a first draft | Drafting workflows using Copilot |
| `👁️ Human Review` | Output awaiting human review | After AI assistance |
| `✅ Approved` | Reviewed and approved by human | Before delivery or publication |
| `🚩 Policy Check` | Requires policy validation | Any compliance question |
| `💡 Idea Captured` | Raw idea submitted, pending review | Ideation Intake |
| `⏸️ Blocked` | Cannot progress | Dependency waiting |
| `📋 Executive Review` | Awaiting executive sign-off | Executive communications |

---

## Part 8: Measurement Commitments

### 8.1 Metrics We Track

| Metric | How We Measure It | Frequency |
|--------|------------------|-----------|
| AI disclosure compliance rate | % of AI-assisted work items with complete disclosure notation in Asana | Weekly |
| Synergy satisfaction | Team retrospective rating (1–5 scale): "Did AI help us produce better work this week?" | Monthly |
| Idea submission rate | Count of ideas submitted to #content-ai-ideas Slack channel | Monthly |
| Escalation event count | Count of escalation triggers activated this period | Monthly |
| Publication cycle time | Days from brief to published content (baseline vs. AI-assisted) | Monthly |

### 8.2 Reporting

Metrics are reviewed in the monthly Governance Retrospective and summarized in a brief monthly note posted to the Content team channel. Quarterly summaries are shared with the CMO.

---

## Part 9: Playbook Change Log

| Version | Date | Changed By | Summary of Changes |
|---------|------|-----------|-------------------|
| v1.0 | 2026-04-01 | Jordan Lee | Initial adoption of GATAF playbook |

---

> **Note:** This is a sample playbook for illustrative purposes. Team names, roles, tools, and policies are fictional. Adapt this example for your team's actual context.

---

*GATAF Sample Playbook | Content & Communications Team*
*Licensed under Apache 2.0 | Part of the GATAF – Governed AI Team Acceleration Framework*
