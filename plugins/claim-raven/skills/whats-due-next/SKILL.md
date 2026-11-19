---
name: whats-due-next
description: Use when a veteran asks what is due, what to do next on their VA claim, where their claim stands, or about deadlines and tasks. Needs the Claim Raven connection.
---

# What is due next

1. Call `list_deadlines_and_tasks` for deadlines, tasks and reminders.
2. Call `get_va_summary`, and `get_va_claim` for any open claim or appeal, to see where each one stands in the veteran's VA.gov copy. Give the `from_va_gov_as_of` date and tell the veteran to check VA.gov for anything newer.
3. Use `list_conditions` to tie each item to a condition.
4. Put the items in date order, soonest first, and say for each one what the veteran needs to do. Dates the veteran or Claim Raven entered are not VA decisions; tell them to check those against their VA letter.

Say plainly what you could not check. This is general information, not legal advice.
