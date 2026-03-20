# North Star: NotebookLM Knowledge System

## Purpose

This document exists to keep the system on course as it grows.

The goal is not to build a large library of extracted conversations.

The goal is to build a **low-noise decision support system** that helps surface reusable patterns, lessons learned, and decision guidance across projects over time.

When new ideas, tools, shortcuts, or automation options appear, this document should be used to judge whether they strengthen the system or distract from it.

---

# 1. North Star Statement

We are building a **curated decision support system** on top of standardized AI extraction.

The system should:

- capture reusable knowledge from conversations and projects  
- preserve high-value insights without accumulating noise  
- support future decision-making, not just memory recall  
- remain simple enough to maintain consistently over time  
- compound trust as the library grows  

If the system becomes harder to maintain, noisier to retrieve from, or less trustworthy over time, it is drifting away from the north star.

---

# 2. What This System Is

This system is:

- a **decision support system**  
- a **curated knowledge layer**  
- a **reusable lessons-learned system**  
- a **pattern retrieval system**  
- a way to preserve high-value thinking across conversations and projects  

It is designed to answer questions like:

- What pattern have we seen before?  
- What approach tends to work best here?  
- What mistake should we avoid repeating?  
- What decision rule should guide this new situation?  
- What earlier concept is this most similar to?  
- What is the current best version of this idea?  

---

# 3. What This System Is Not

This system is **not**:

- a transcript archive  
- a dumping ground for every conversation  
- a generic note-taking system  
- a project document repository  
- a comprehensive reference encyclopedia  
- a system where every extracted insight is stored equally  
- a system that depends on perfect tagging to work  

If something belongs in raw history, personal notes, or project storage but does not improve future decisions, it does not belong in the active knowledge system.

---

# 4. Core Design Principle

## Consistency over completeness

The system should favor:

- consistent structure  
- constrained decision-making  
- selective inclusion  
- stable vocabulary  
- repeatable curation  

over:

- storing everything  
- capturing every nuance  
- creating many special cases  
- over-modeling edge cases  
- adding complexity too early  

A smaller, cleaner, more trusted system is better than a larger, noisier one.

---

# 5. System Model

The system flow is:

Conversation / Project  
→ Universal Extraction Prompt  
→ Review Package  
→ AI-Assisted Curation Suggestions  
→ Human Decision Layer  
→ Selective Promotion into Atomic Assets  
→ Domain Notebook(s) in NotebookLM  
→ Decision Retrieval  

## Responsibilities

### Extraction
Responsible for:

- normalization  
- structure  
- clarity  
- reusable insight capture  

Extraction is **stateless** and must work across domains.

### Curation
Responsible for:

- splitting  
- classification  
- deduplication  
- tagging  
- routing  
- canonical integrity  

Curation handles cross-document logic and shapes the system.

---

# 6. Hard Rules

## Rule 1: Do not store everything
Selective promotion is mandatory.

## Rule 2: One concept → one best version
Every concept family converges to a single canonical asset.

## Rule 3: Canonical assets > tags
Tags support retrieval. Canonicals define truth.

## Rule 4: Extraction is universal
No domain-specific assumptions in the extraction prompt.

## Rule 5: Curation must stay simple
If it becomes heavy, the system will decay.

## Rule 6: Decision value is the filter
Only include items that improve future decisions.

## Rule 7: Archive aggressively
When uncertain, do not promote.

---

# 7. System Goals

## Primary Goals

### Maximize retrieval quality
Surface the right concept with minimal noise.

### Minimize duplication
Avoid competing versions of the same idea.

### Preserve trust
Results should consistently be worth reading.

### Support future decisions
Outputs must guide action, not just explain.

### Stay maintainable
The system must remain usable long-term.

---

# 8. Success Criteria

The system is succeeding when:

- relevant patterns surface quickly  
- similar ideas are grouped cleanly  
- new work benefits from past insights  
- duplication stays low  
- curation remains fast  
- the active set stays high signal  
- trust increases over time  

The system is failing when:

- many results say the same thing  
- concepts fragment into multiple versions  
- the active set grows without control  
- tagging becomes inconsistent  
- curation feels too heavy  
- results feel descriptive, not actionable  

---

# 9. Extraction Output

Each review package may include:

- Foundations  
- Patterns  
- Case Study  
- Decision Playbook  

These are **review components**, not automatic stored assets.

---

# 10. Promotion Model

## Core Principle

Extraction  
→ Review Package  
→ Selective Promotion  
→ Active Knowledge System  

This prevents:

- duplication  
- noise  
- trust decay  

---

# 11. Asset Model

Allowed asset types:

- Foundation  
- Pattern  
- Case Study  
- Decision Playbook Entry  

Do not expand casually.

---

# 12. Canonical Asset Model

Each concept family contains:

- one canonical asset  
- optional supporting assets  
- optional archived/superseded versions  

## Canonical
Best current version of a reusable idea.

## Supporting
Examples or clarifications.

## Superseded
Replaced versions.

## Archive
Inactive storage.

---

# 13. Status Model

Every asset must have one:

- Canonical  
- Supporting  
- Archive  
- Superseded  

This prevents “everything is equal.”

---

# 14. Promotion Criteria

## Canonical (ALL required)

- reusable  
- decision-relevant  
- best available version  
- actionable  

## Supporting (ANY)

- strong example  
- edge case  
- reinforcement  

## Archive

- duplicate  
- weak  
- non-reusable  
- descriptive  

---

# 15. Concept Families

Each concept family has:

- stable name  
- one canonical  
- optional supporting assets  

Purpose:

- prevent drift  
- group knowledge  
- stabilize retrieval  

---

# 16. Notebook Structure

Notebook = domain

Examples:

- AI Systems  
- Product / UX  
- Finance  
- Personal Systems  

Avoid:

- project notebooks  
- topic fragmentation  

---

# 17. Tagging Model

Use exactly 5 categories:

- Domain (1)  
- Type (1)  
- Concept (1–3)  
- Priority (1)  
- Status (1)  

---

# 18. Tagging Rules

- Use controlled vocabulary  
- Max 3 concept tags  
- Tag after classification  
- Avoid synonyms  
- Do not over-tag  

---

# 19. Deduplication Model

Each asset is:

- New  
- Refinement  
- Duplicate  

## Actions

New → add  
Refinement → update canonical  
Duplicate → archive/discard  

---

# 20. Deduplication Questions

- Is the trigger different?  
- Is the action different?  
- Is the failure mode different?  
- Is it better?  

---

# 21. AI-Assisted Curation

## AI can:

- split content  
- suggest classification  
- suggest tags  
- find similar concepts  

## AI cannot:

- promote canonicals  
- finalize merges  
- control inclusion  

Human judgment is required.

---

# 22. Human Decision Layer

For each asset:

1. New / refinement / duplicate  
2. Canonical / supporting / archive  
3. Concept family  
4. Accept or adjust tags  

---

# 23. Curation Bias

Prefer:

- discard  
- archive  

Avoid promoting marginal content.

---

# 24. Workflow

1. Read extraction  
2. Identify candidate assets  
3. Classify  
4. Assign status  
5. Update canonical if needed  
6. Tag  
7. Route to notebook  
8. Stop  

---

# 25. Time Discipline

Curation must be:

- fast  
- structured  
- repeatable  

Avoid perfectionism.

---

# 26. What to Avoid

- storing everything  
- over-tagging  
- too many notebooks  
- over-splitting  
- vocabulary drift  
- multiple canonicals  
- descriptive-only assets  
- premature automation  

---

# 27. Failure Modes

### Document graveyard
Too many stored assets.

### Canonical drift
Multiple active versions.

### Tag explosion
Too many tags.

### Retrieval noise
Too many similar results.

### Human fatigue
Too much effort required.

### Automation overreach
Incorrect automated decisions.

---

# 28. Decision Filters

Before promoting:

- Is it reusable?  
- Is it decision-useful?  
- Is it distinct?  
- Is it high quality?  

---

# 29. Expansion Principles

Before adding complexity, ask:

- Does this improve retrieval?  
- Does this reduce noise?  
- Does this preserve simplicity?  
- Will it scale?  

---

# 30. What Must Stay Stable

- universal extraction  
- promotion model  
- canonical model  
- status field  
- domain notebooks  
- constrained tagging  
- human control  
- discard bias  

---

# 31. What Can Evolve

- vocabulary  
- notebook boundaries  
- AI assistance  
- supporting asset usage  

Only evolve when needed.

---

# 32. Operational Philosophy

The system should **compound**:

- best ideas survive  
- weak ideas disappear  
- canonicals improve  
- trust increases  

---

# 33. Final Test

Does this make the system:

- cleaner  
- more reusable  
- easier to trust  
- better for decisions  

Or:

- larger  
- noisier  
- harder to maintain  

---

# 34. Summary

The system must remain:

- universal at extraction  
- selective at promotion  
- disciplined at curation  
- concept-centered  
- low-noise  
- human-governed  
- simple  

## North Star

**Trusted, compounding, decision-useful knowledge**
