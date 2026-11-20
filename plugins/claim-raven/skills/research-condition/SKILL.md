---
name: research-condition
description: Use when a veteran or anyone helping them wants to know how VA handles a condition, including how it can be service connected, how VA rates it, what evidence and exams matter, and how the Board of Veterans' Appeals has decided similar claims. Needs the Claim Raven connection.
---

# Research a condition

1. Call `research_condition` for the condition with the topic that fits the question (`service_connection`, `rating`, `evidence`, `exam`).
2. Use `find_va_authority` for the law on the question and `lookup_va_rules` for the exact rule text.
3. Call `get_board_outcomes` for how often the Board granted, denied or remanded the condition. If this account can, use `study_board_decisions` or `search_board_decisions` and `read_board_decision` for examples. Board figures describe past decisions, not anyone's chances.
4. If the veteran wants it tied to their own file, use `list_conditions` and `search_records` when the connection allows.

Cite every source with its citation and date, and quote official text only from these results. If a source comes back stored or unavailable, say so with its date. This is general information, not legal or medical advice.
