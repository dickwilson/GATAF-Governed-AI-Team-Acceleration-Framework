# GATAF Collaboration Plan — Plan Mode

> **#aicollaboration** | Governed by GATAF Principle 4 (Transparency) and Principle 5 (On-Demand Status Determinability)

This document is the living record of the plan-mode collaboration between:

| Role | Identity | Abbreviation used in this document |
|---|---|---|
| Human (Framework Originator) | Richard "Dick" Wilson | `human` |
| AI Collaborator (GitHub Copilot) | GitHub Copilot coding agent (`copilot-swe-agent[bot]`) | `copilot` |

Every entry below is **explicitly labelled** with its author so any reader can determine, in under 30 seconds, who contributed what.

---

## How Plan Mode Works

**Plan mode** is an explicit collaboration state in which `human` and `copilot` jointly develop a shared plan before any implementation begins.  The rules are:

1. **`human` opens the session** – establishes intent, constraints, and success criteria in their own words.
2. **`copilot` proposes a structured plan** – breaks intent into discrete, verifiable steps and surfaces assumptions.
3. **`human` reviews and amends** – accepts, rejects, or modifies each proposed step.  No step is locked until `human` explicitly approves it.
4. **Both parties sign off** – the agreed plan is recorded here before any file changes are made.
5. **All subsequent work traces back to this plan** – every commit references which plan step it implements.

Plan mode satisfies GATAF Principle 4 because the AI's reasoning is visible at every step, not reconstructed after the fact.

---

## Session 1 — Establish Transparency in Collaboration

**Opened:** 2026-03-08  
**Status:** `IN PROGRESS`

### Intent — `human`

> *"in plan mode, we you ('Github.Copilot') and me ('i.Richard('Dick')Wilson.human') are to collaborate, and provide transparency #aicollaboration"*

**Human's success criteria (paraphrased by `copilot` for confirmation):**

- There must be a visible, durable record of who said what during planning.
- The collaboration mode must be named ("plan mode") and its rules must be written down.
- The `#aicollaboration` tag must be applied to all artifacts produced in this session.
- The work must comply with GATAF Principle 4 (Transparency).

> **⬛ `human` – please confirm or correct the success criteria above before implementation proceeds.**

---

### Proposed Plan — `copilot`

The following steps were proposed by `copilot` based on the human's intent.  Each step is marked with its current status.

| # | Step | Owner | Status |
|---|---|---|---|
| 1 | Create `PLAN.md` (this file) as the transparent collaboration record | `copilot` | ✅ Done |
| 2 | Create `templates/plan-mode-template.md` so other teams can follow the same protocol | `copilot` | ✅ Done |
| 3 | Update `README.md` to reference plan mode and the #aicollaboration tag | `copilot` | ✅ Done |
| 4 | `human` reviews and approves (or amends) this plan | `human` | ⬛ Awaiting |
| 5 | Mark session status `COMPLETE` and record sign-off | both | ⬛ Awaiting |

**Assumptions made by `copilot`:**

- The repository's primary deliverable for this issue is documentation, not executable code (consistent with the current repo structure).
- "Transparency" means explicit author labelling inside documents, not only commit metadata.
- Other framework documents from parallel work branches (PR #1) are acknowledged but not merged here; this branch focuses solely on the plan-mode protocol.

> **⬛ `human` – please confirm assumptions or flag any that are incorrect.**

---

### Amendments — `human`

*This section is reserved for Dick Wilson's amendments to the proposed plan.*

---

### Sign-off

| Party | Approved | Date |
|---|---|---|
| `human` — Richard "Dick" Wilson | ⬛ Pending | — |
| `copilot` — GitHub Copilot | ✅ Proposed | 2026-03-08 |

---

## Transparency Audit Trail

All changes made to this repository as part of this collaboration session are listed below with explicit attribution.

| File | Action | Author | Commit |
|---|---|---|---|
| `PLAN.md` | Created | `copilot` | *(see git log)* |
| `templates/plan-mode-template.md` | Created | `copilot` | *(see git log)* |
| `README.md` | Updated | `copilot` | *(see git log)* |

> This audit trail is maintained by `copilot` and should be verified by `human` before the session is marked complete.
