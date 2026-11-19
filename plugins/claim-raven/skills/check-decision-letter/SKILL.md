---
name: check-decision-letter
description: Use when a veteran wants to understand a VA decision letter, what VA decided on each issue and why, and what their review options and time limits are. Needs the Claim Raven connection.
---

# Check a VA decision letter

1. Call `whoami` to see what this connection can read.
2. Get the letter's text. `list_va_documents` shows which letters VA sent and their dates, but never their contents. To read a letter, use `list_records` and `read_record_pages` when the veteran saved it in Claim Raven and this connection can read records. Otherwise ask the veteran to paste the parts they want checked. Do not interpret a letter you have not read.
3. For each issue, say what VA decided, the reasons it gave, and the evidence it said was missing. Quote the letter only from what you read, with its date and page.
4. Show the law VA applied with `find_va_authority` and `lookup_va_rules`. Use `research_condition` with topic `service_connection` or `rating` where it helps.
5. Explain the review options (Supplemental Claim, Higher-Level Review, Board appeal) and their time limits in plain words, counting from the date on the letter. The letter's date controls. Do not choose for the veteran.

Cite every source with its date. Ask for facts only the veteran knows instead of guessing. Say plainly what you could not check. This is general information, not legal advice; suggest checking important points with a VA-accredited representative.
