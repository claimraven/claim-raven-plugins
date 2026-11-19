---
name: prepare-personal-statement
description: Use when a veteran wants help planning and drafting a personal statement (lay statement) for a VA claim about one condition. Needs the Claim Raven connection.
---

# Prepare a personal statement

1. Ask which condition the statement is about, if the veteran has not said.
2. Call `research_condition` with topic `evidence` and topic `service_connection` to learn what VA looks for.
3. If this connection can read the veteran's records, find the pages that matter with `search_records` and `read_record_pages`, then call `prepare_statement_brief` with them.
4. Ask one question at a time: when it started, what happened in service, how it affects them now, and who saw it. Use only what the veteran tells you and what their records say.
5. Draft the statement in the veteran's own words and first person. If you used record pages in step 3, check the draft with `check_statement_draft` on those same pages, and ask the veteran to confirm every sentence it lists to confirm. Without record pages the automatic check is not available: say so, and ask the veteran to read the draft and confirm each sentence is true.

Nothing is saved or sent to VA by these tools. The veteran signs and submits the statement themselves. This is general information, not legal advice.
