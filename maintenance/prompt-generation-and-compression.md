Development Note
This document defines prompt maintenance rules for developers.
It must never be included in runtime agent instructions.

---

You are helping prepare instructions for a Microsoft Copilot agent.

The final instructions must fit within an 8000 character limit.

This process protects the behavioral integrity of the instructions while compressing them to fit the Copilot limit.

------------------------------------------------------------

Instruction Governance

Sections labeled [FOUNDATION], [STRICT], and [REQUIRED] define the behavioral contract of the agent.

These sections must not be removed or functionally weakened during compression.

Allowed changes:
- shorten wording
- remove repetition
- combine sentences

Not allowed:
- removing behavioral constraints
- weakening escalation or investigation safeguards
- altering operational meaning

[FLEXIBLE] sections may be reduced more aggressively.

------------------------------------------------------------

Stage 1 — Labeling

Read the instructions and label each section with one of the following tags:

[FOUNDATION] — core identity, purpose, and boundaries of the agent  
[STRICT] — non-negotiable rules or constraints  
[REQUIRED] — operational behaviors the agent must follow  
[FLEXIBLE] — formatting, tone, or optional preferences

Do NOT change the wording yet. Only add the labels.

------------------------------------------------------------

Stage 2 — Compression

Once labeling is complete, compress the instructions so the total length is under 8000 characters.

Compression rules:

1. Preserve the meaning of all [FOUNDATION], [STRICT], and [REQUIRED] sections.
2. These sections must remain clearly identifiable with their labels.
3. Reduce redundancy and verbosity in [FLEXIBLE] sections first.
4. Combine repetitive sentences where possible.
5. Prefer shorter wording but do not remove important constraints.
6. Maintain logical section structure.
7. Prefer removing examples before removing rules.
8. Preserve section ordering and logical grouping of instructions.

Return the final compressed instruction set with labels still included as proper Markdown enclosed in a single outer MD block.

------------------------------------------------------------

Stage 3 — Review & Evaluation

After compression is complete, compare the compressed result with the original instructions and evaluate for loss.

Provide the following analysis:

Overall Result

What Was Preserved Correctly

What Changed (Minor Losses)

What Was Intentionally Reduced (Good)

What Was Lost (Bad)

Character Reduction Result

Final Verdict

Target: under 8000 characters.