# Targeted Deepening: Tagging System

This document defines how tagging should be used to support retrieval without becoming a source of noise or inconsistency.

Tagging is a **support system**, not the core system.

The core system is:
- canonical assets
- concept families
- curation decisions

Tags exist to:
- improve retrieval
- enable grouping
- reduce search friction

They do NOT define truth.

---

# 1. Tagging Philosophy

## Principle 1: Tags support, they do not lead

Tags should never:
- replace concept families
- define relationships between ideas
- determine what is canonical

If tagging becomes the primary way to understand the system, the system is drifting.

---

## Principle 2: Constrained > expressive

The goal is not to perfectly describe an asset.

The goal is to:
- categorize it consistently
- make it retrievable
- avoid fragmentation

---

## Principle 3: Stability over time

Tag vocabulary should change slowly.

Frequent tag creation leads to:
- duplication
- synonym drift
- broken retrieval

---

# 2. Tag Model (Locked)

Each asset must have:

- Domain (1)
- Type (1)
- Concept (1–3)
- Priority (1)
- Status (1)

No additional dimensions without system redesign.

---

# 3. Tag Definitions

## Domain

Defines the broad area of application.

Rules:
- exactly 1
- must map to a NotebookLM domain
- must be stable and reusable

Examples:
- AI Systems
- Product UX
- Finance

---

## Type

Defines the asset type.

Rules:
- exactly 1
- must match asset model

Values:
- Foundation
- Pattern
- Case
- Decision

---

## Concept

Defines the concept family.

Rules:
- 1 to 3 maximum
- must align with concept family anchor
- must use controlled vocabulary

This is the most sensitive tag.

---

## Priority

Defines relative importance.

Rules:
- exactly 1
- do not overthink

Values:
- High → broadly reusable, important
- Medium → useful but not central
- Low → niche or situational

---

## Status

Defines lifecycle.

Rules:
- exactly 1
- must match asset state

Values:
- Canonical
- Supporting
- Archive
- Superseded

---

# 4. Tagging Workflow

Tags are applied ONLY after:

1. classification (new / refinement / duplicate)
2. status decision (canonical / supporting / archive)

Never tag before those decisions.

---

# 5. Concept Tag Control (Most Critical)

## Rule 1: Concept tags must map to concept families

If a concept tag exists, there must be a corresponding concept family.

If not, do not create the tag.

---

## Rule 2: No synonym creation

Before creating a new concept tag, ask:

- Does an existing tag cover this 80%?
- Is this actually a new concept, or just new wording?

If similar tags already exist:
→ reuse one
→ do not create a new one

---

## Rule 3: Reuse threshold

Only create a new concept tag if:

- it represents a distinct reusable idea
- it will likely be used again
- it cannot be merged with an existing concept

---

## Rule 4: Hard limit

Never exceed 3 concept tags per asset.

If more are needed:
→ the asset is too broad or unclear

---

# 6. Tagging Anti-Patterns

## Over-tagging

Symptom:
Too many tags per asset.

Fix:
Reduce to essential categories.

---

## Narrative tagging

Symptom:
Tags try to describe everything in the asset.

Fix:
Tags should classify, not narrate.

---

## Synonym drift

Symptom:
Multiple tags with similar meaning.

Fix:
Consolidate to one.

---

## Project-specific tags

Symptom:
Tags tied to one project or conversation.

Fix:
Remove — not reusable.

---

## Tag-first behavior

Symptom:
Assigning tags before understanding the asset.

Fix:
Always classify first.

---

# 7. Tagging and Retrieval

Tags improve retrieval by:

- enabling filtering
- grouping related assets
- narrowing search space

But:

Retrieval quality depends primarily on:
- canonical clarity
- concept family structure
- low duplication

Tags only assist.

---

# 8. Tagging and Scale

As the system grows:

Do:
- reuse existing tags
- consolidate similar tags
- periodically review vocabulary

Do not:
- expand tag dimensions
- allow uncontrolled growth
- create tags for edge cases

---

# 9. Maintenance Rules

Occasionally:

- review concept tag list
- merge duplicates
- remove unused tags

But:

Do not turn this into heavy maintenance.

Tagging should remain lightweight.

---

# 10. Final Principle

If tagging becomes complex:

The system is compensating for a deeper issue.

That issue is usually:
- weak canonical structure
- unclear concept families
- poor curation decisions

Fix those first.

---

# 11. Summary

Tagging must remain:

- constrained
- consistent
- secondary to canonical structure
- easy to apply
- resistant to drift

## Final Standard

Tags should make the system easier to use.

They should never make it harder to maintain.
