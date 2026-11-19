---
name: prepare-for-cp-exam
description: Use when a veteran has a VA compensation and pension (C&P) exam coming up for a condition and wants to know what the examiner will ask and measure and what to tell them. Needs the Claim Raven connection.
---

# Prepare for a C&P exam

1. Ask which condition the exam is for, if the veteran has not said.
2. Call `research_condition` with topic `exam`, then topic `rating`, to learn what the examiner usually asks and measures and how VA rates the condition. Use `lookup_va_rules` for the rating criteria text.
3. If this connection can read the veteran's workspace, use `list_conditions`, `search_records` and `read_record_pages` to find what their records already say about the condition, and `list_deadlines_and_tasks` for the exam date.
4. Ask the veteran about symptoms on a bad day, how often they happen, and how they affect work and daily life. Do not invent or suggest symptoms they have not described.
5. Help them make a short list of points to tell the examiner, in their own words.

Cite every source with its date. Say plainly what you could not check. This is general information, not medical or legal advice.
