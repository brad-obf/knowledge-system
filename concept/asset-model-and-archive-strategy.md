# Targeted Deepening: Asset Model and Archive Strategy

This document extends the North Star to lock two areas that will determine long-term system quality:

1. Asset Model (Canonical + Supporting structure)
2. Archive Strategy (what happens to everything not promoted)

The goal is to prevent:
- canonical drift
- supporting asset creep
- archive becoming a second noisy system
- loss of high-value ideas due to over-discarding

---

# 1. Asset Model (Expanded)

## Core Principle

The system is **concept-centered**, not document-centered.

Every promoted asset must belong to a **Concept Family**.

---

## Concept Family Structure

Each concept family contains:

- **Concept Name (stable, reusable)**
- **Canonical (exactly 1 active)**
- **Supporting (0–N)**
- **Superseded (optional)**
- **Archive (external / inactive)**

---

## Concept Name (Anchor)

Each concept family must have a stable name.

This name is used for:
- deduplication
- tagging consistency
- retrieval clarity
- avoiding synonym drift

### Naming Rules

- short but descriptive
- reusable across contexts
- not tied to a specific project
- avoid synonyms once established

### Examples

- Extraction vs Curation Separation  
- Constraint-First Instruction Design  
- Promote Selectively, Not Completely  

---

## Canonical Asset (Refined Definition)

### Purpose

The canonical asset is the **single source of truth** for a concept.

It should represent:
- the best current thinking
- the most reusable version
- the clearest decision guidance

---

### Canonical Requirements (ALL required)

- reusable across contexts  
- decision-relevant  
- clearly better than existing OR fills a gap  
- expressed as an actionable rule or principle  
- stable enough to be referenced repeatedly  

---

### Canonical Behavior Rules

- Only ONE active canonical per concept family  
- Must be updated when a better version appears  
- Must absorb refinements instead of competing with them  
- Should remain concise and high-signal  

---

### When to Update Canonical

Update when a refinement provides:

- clearer trigger conditions  
- better decision framing  
- stronger generalization  
- improved actionability  
- removal of ambiguity  

Do NOT create a second canonical for the same concept.

---

## Supporting Assets (Refined)

### Purpose

Supporting assets exist to **strengthen understanding**, not to compete with canonicals.

---

### When to Create Supporting

Only when one of the following is true:

- strong real-world example  
- clarifies an edge case  
- demonstrates failure mode  
- reinforces canonical in a meaningful way  

---

### Supporting Rules

- Must attach to a concept family  
- Must NOT restate the canonical in slightly different words  
- Must NOT introduce competing interpretations  
- Should be limited in number  

---

### Anti-Drift Rule

If a supporting asset starts to feel like:
- a better version
- a clearer version
- a more general version

Then it is a **refinement**, not supporting → update canonical.

---

## Superseded Assets

### Purpose

Preserve evolution when useful.

---

### When to Keep

Only if:

- understanding evolution matters  
- decision tradeoffs changed over time  
- historical context is useful  

Otherwise, archive instead.

---

### Rules

- Must not compete with canonical  
- Must be clearly marked as outdated  
- Should not appear in normal retrieval  

---

# 2. Archive Strategy (Expanded)

## Core Principle

Archive is not a secondary knowledge base.

Archive is:
- a **holding zone**
- not part of active retrieval
- not expected to be queried regularly

---

## Why Archive Matters

Without a clear archive strategy:

- duplication creeps back in  
- weak ideas stay active  
- retrieval noise increases  
- trust decreases  

With a clear archive:

- active system stays clean  
- history is preserved safely  
- decisions remain focused  

---

## What Goes to Archive

An asset should be archived if:

- duplicate with no meaningful delta  
- weaker version of a concept  
- too project-specific  
- descriptive but not decision-useful  
- unclear value  
- early-stage thinking not worth promoting  

---

## Archive vs Discard

### Archive when:

- might contain future insight  
- useful for traceability  
- borderline reusable  
- supports future reflection  

### Discard when:

- clearly redundant  
- low quality  
- no decision value  
- no future usefulness  

---

## Archive Rules

- Archived items are NOT part of NotebookLM active set  
- Archive should not grow without awareness  
- Archive should not become a second working system  
- Archive is optional for retrieval, not default  

---

## Archive Storage Philosophy

Keep archive:

- accessible if needed  
- separate from active knowledge  
- low-maintenance  

Do NOT:
- tag heavily  
- curate deeply  
- attempt to organize perfectly  

---

## Archive Review (Optional)

Occasionally:

- revisit archive for missed canonicals  
- extract rare insights if needed  

But:

Do not make archive maintenance a routine burden.

---

# 3. Promotion + Archive Interaction

## Decision Path (Final)

For each candidate asset:

### Step 1 — Classification

- New  
- Refinement  
- Duplicate  

---

### Step 2 — Outcome

#### New
→ Canonical OR Supporting

#### Refinement
→ Update Canonical  
→ Archive or keep as Supporting (if example value exists)

#### Duplicate
→ Archive OR Discard  

---

## Key Rule

Never allow:
- duplicate + canonical both active  
- refinement + canonical both active without merge  
- supporting assets that restate canonical  

---

# 4. System Balance

The system should maintain this ratio:

- **Few canonicals (high quality)**  
- **Limited supporting (high value only)**  
- **Most content archived or discarded**  

If this ratio flips, the system is drifting.

---

# 5. Early Warning Signs

## Asset Model Issues

- multiple canonicals emerging  
- supporting assets feel redundant  
- canonicals not updated over time  

## Archive Issues

- archive grows rapidly without control  
- archived items start being referenced frequently  
- uncertainty about what belongs where  

---

# 6. Correction Actions

If issues appear:

### Too many canonicals
→ merge concept families  
→ enforce single source of truth  

### Supporting overload
→ remove weak examples  
→ keep only highest signal  

### Archive bloat
→ increase discard threshold  
→ tighten promotion rules  

---

# 7. Final Principle

The system should behave like:

- a **compressed, high-signal layer of knowledge**
- not a full record of everything learned

You are not preserving everything.

You are preserving:
- what matters
- what repeats
- what guides decisions

---

# 8. Summary

## Asset Model

- concept-centered  
- one canonical per concept  
- supporting only when valuable  
- refinement updates canonical  

## Archive Strategy

- protects system from noise  
- not part of active retrieval  
- store selectively  
- discard aggressively when appropriate  

---

## Final Standard

The system should continuously move toward:

- fewer, stronger canonicals  
- clearer concept families  
- minimal supporting noise  
- clean active knowledge  
- controlled archive  

This is what enables long-term compounding without degradation.
