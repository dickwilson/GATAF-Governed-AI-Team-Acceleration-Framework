# GATAF Plan-Mode Collaboration Template

> **#aicollaboration** | Governed by GATAF Principle 4 (Transparency) and Principle 5 (On-Demand Status Determinability)

Copy this template to create a new plan-mode session document.  Replace every `[placeholder]` with real content before beginning implementation.

---

## Participants

| Role | Identity | Abbreviation used in this document |
|---|---|---|
| Human | `[full name]` | `human` |
| AI Collaborator | `[AI tool name and version]` | `copilot` (or preferred label) |

---

## How Plan Mode Works

Plan mode is an explicit collaboration state in which `human` and `copilot` jointly develop a shared plan **before** any implementation begins.

**Rules:**

1. **`human` opens the session** — states intent, constraints, and success criteria in their own words.
2. **`copilot` proposes a structured plan** — breaks intent into discrete, verifiable steps and surfaces assumptions.
3. **`human` reviews and amends** — accepts, rejects, or modifies each proposed step.  No step is locked until `human` explicitly approves it.
4. **Both parties sign off** — the agreed plan is recorded here before any file changes are made.
5. **All subsequent work traces back to this plan** — every commit references which plan step it implements.

---

## Session — `[Short Session Title]`

**Opened:** `[YYYY-MM-DD]`  
**Status:** `DRAFT` | `IN PROGRESS` | `COMPLETE`

### Intent — `human`

> *"[Paste the human's original words here, verbatim, without editing.]*"

**Human's success criteria (proposed by `copilot` for confirmation):**

- [Criterion 1]
- [Criterion 2]
- [Criterion 3]

> **⬛ `human` — please confirm or correct the success criteria above before implementation proceeds.**

---

### Proposed Plan — `copilot`

| # | Step | Owner | Status |
|---|---|---|---|
| 1 | [First step description] | `copilot` / `human` | ⬛ Pending |
| 2 | [Second step description] | `copilot` / `human` | ⬛ Pending |
| 3 | [Third step description] | `copilot` / `human` | ⬛ Pending |
| 4 | `human` reviews and approves (or amends) this plan | `human` | ⬛ Awaiting |
| 5 | Mark session status `COMPLETE` and record sign-off | both | ⬛ Awaiting |

**Assumptions made by `copilot`:**

- [Assumption 1]
- [Assumption 2]

> **⬛ `human` — please confirm assumptions or flag any that are incorrect.**

---

### Amendments — `human`

*[Human adds any changes, additions, or corrections to the plan here.]*

---

### Sign-off

| Party | Approved | Date |
|---|---|---|
| `human` — [Name] | ⬛ Pending | — |
| `copilot` — [AI tool] | ⬛ Pending | — |

---

## Transparency Audit Trail

| File | Action | Author | Commit |
|---|---|---|---|
| *(filled in as work progresses)* | | | |

> **Attribution key:**
> - `human` = changes made directly by the human participant
> - `copilot` = changes proposed and implemented by the AI collaborator
> - `both` = changes produced through real-time back-and-forth in the same session

---

## Compliance Checklist

Use this checklist before marking the session `COMPLETE`.

- [ ] Every plan step has a named owner (`human` or `copilot`)
- [ ] Human's original intent is quoted verbatim (unchanged)
- [ ] All assumptions made by `copilot` are listed and human-confirmed
- [ ] Sign-off from both parties is recorded
- [ ] Audit trail lists every file touched with author attribution
- [ ] `#aicollaboration` tag appears at the top of the document
- [ ] Document satisfies GATAF Principle 4: AI contribution is explainable in under 30 seconds
