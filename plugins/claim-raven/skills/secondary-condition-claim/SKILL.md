---
name: secondary-condition-claim
description: Use when a veteran thinks one condition was caused or made worse by a condition VA already service connected, and wants to know what a secondary service connection claim needs. Needs the Claim Raven connection.
---

# Secondary condition claim

1. Confirm the two conditions: the one to claim, and the service-connected condition the veteran thinks caused or worsened it. Use `get_va_summary` to check what VA has actually granted. Say "service connected" only for a condition VA granted.
2. Call `research_condition` for the condition to claim with topic `service_connection`, route `secondary` and `related_condition` set to the other condition, and `find_va_authority` for the rules on secondary service connection (38 CFR 3.310).
3. If this account can, call `study_board_decisions` with the same condition, route `secondary` and `related_condition` to see how similar claims were granted. Board figures describe past decisions, not this veteran's chances.
4. List each thing that must be shown, the evidence that usually proves it, and what the veteran already has or is missing. If this connection can read their records, check with `search_records`.
5. A medical opinion is usually needed. Help the veteran write questions to ask their doctor, never the opinion itself.

Cite every source with its date. Say plainly what you could not check. This is general information, not legal or medical advice.
