---
name: board-case-research
description: Use when an accredited representative or attorney wants Board of Veterans' Appeals decisions on facts like their case: how often a condition is granted, denied or remanded, which evidence and theories won, and decisions to read and cite. Needs a Claim Raven Pro connection.
---

# Board case research

Never ask for or use client names, file numbers or records. Describe the case by condition, theory and facts only. No client records are available through this connection; tell the user not to paste client records into this AI app unless their agreement with the AI company covers them.

1. Call `get_board_outcomes` for the condition's grant, denial and remand figures. They describe past decisions, not a case's chances.
2. Call `study_board_decisions` with the condition and, where it applies, the related condition, to see how similar claims were won.
3. Use `search_board_decisions` for decisions on the specific facts, then `read_board_decision` to read the ones that matter. Quote a decision only from what you read, with its citation number and date.
4. Summarize what the granted decisions had in common (evidence, opinions, theories) and what was missing in the denials and remands.

Cite every decision with its citation number and date. Board decisions are nonprecedential. Say plainly what you could not check.
